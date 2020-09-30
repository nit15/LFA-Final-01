# IDs
jay01.webflow.io:
`5f6d832f31efc5edb474e9bd`

### Event Types
1. Scrolling events
2. Click events



# 1. Scrolling Events
If Scrolling event use Next number (previousEventNumber+1)

### Event Number
```javascript
"e-6"{
        .
        .
        .
},
{"[Event Number] (e-7) ": {
            "id": "[Event Number] (e-7)",
            "name": "",
            "eventTypeId": "SCROLLING_IN_VIEW",
            "action": {
                "id": "",
                "actionTypeId": "GENERAL_CONTINUOUS_ACTION",
                "config": {
                    "actionListId": "[ACTION ID]", // Important
                    "affectedElements": {},
                    "duration": 0
                }
            },
            "mediaQueries": ["main", "medium", "small", "tiny"],
            "target": {
                "appliesTo": "ELEMENT",
                "styleBlockIds": [],
                "id": "[jay01.webflow.io]|044f42e9-e1ed-8450-9d40-c84e018e2053"
            }, // Important
            "targets": [],
            "config": [{
                "continuousParameterGroupId": "[ACTION ID with -p]", //  Important
                "smoothing": 51,
                "startsEntering": true,
                "addStartOffset": false,
                "addOffsetValue": 50,
                "startsExiting": false,
                "addEndOffset": false,
                "endOffsetValue": 50
            }],
            "createdOn": 1601117333932
        },
}
```

### ACTION
```javascript
"[Action ID]": {
            "id": "[Action ID]",
            "title": "section1",
            "continuousParameterGroups": [{
                "id": "[Action ID]    -p",
                "type": "SCROLL_PROGRESS",
                "parameterLabel": "Scroll",
                "continuousActionGroups": [{
                    "keyframe": 0,
                    "actionItems": [{
                        "id": "[Action ID]  -n",
                        "actionTypeId": "STYLE_OPACITY",
                        "config": {
                            "delay": 0,
                            "easing": "",
                            "duration": 500,
                            "target": {
                                "useEventTarget": "CHILDREN",
                                "selector": ".cozyheading",
                                "selectorGuids": ["7619d1af-45eb-9bce-e1f1-372b74f488b8"]
                            },
                            "value": 0,
                            "unit": ""
                        }
                    }, {
                        "id": "[Action ID]  -n-3",
                        "actionTypeId": "TRANSFORM_SCALE",
                        "config": {
                            "delay": 0,
                            "easing": "",
                            "duration": 500,
                            "target": {
                                "useEventTarget": "CHILDREN",
                                "selector": ".cozyspot",
                                "selectorGuids": ["e3d19bd7-5bb1-1c4b-6c26-ecf953514c58"]
                            },
                            "xValue": 0.3,
                            "yValue": 0.3,
                            "locked": true
                        }
                    }, {
                        "id": "[Action ID]  -n-4",
                        "actionTypeId": "STYLE_OPACITY",
                        "config": {
                            "delay": 0,
                            "easing": "",
                            "duration": 500,
                            "target": {
                                "useEventTarget": "CHILDREN",
                                "selector": ".cozyspot",
                                "selectorGuids": ["e3d19bd7-5bb1-1c4b-6c26-ecf953514c58"]
                            },
                            "value": 0.1,
                            "unit": ""
                        }
                    }, {
                        "id": "[Action ID]  -n-5",
                        "actionTypeId": "TRANSFORM_MOVE",
                        "config": {
                            "delay": 0,
                            "easing": "",
                            "duration": 500,
                            "target": {
                                "useEventTarget": "CHILDREN",
                                "selector": ".cozyspot",
                                "selectorGuids": ["e3d19bd7-5bb1-1c4b-6c26-ecf953514c58"]
                            },
                            "xValue": 43,
                            "xUnit": "VW",
                            "yUnit": "PX",
                            "zUnit": "PX"
                        }
                    }, {
                        "id": "[Action ID]  -n-6",
                        "actionTypeId": "STYLE_OPACITY",
                        "config": {
                            "delay": 0,
                            "easing": "",
                            "duration": 500,
                            "target": {
                                "selector": ".nerdyarticle",
                                "selectorGuids": ["4d8a29e[Action ID]  -eef5-5d19-ae9f-edd364c5062b"]
                            },
                            "value": 0,
                            "unit": ""
                        }
                    }, {
                        "id": "[Action ID]  -n-7",
                        "actionTypeId": "TRANSFORM_MOVE",
                        "config": {
                            "delay": 0,
                            "easing": "",
                            "duration": 500,
                            "target": {
                                "selector": ".nerdyarticle",
                                "selectorGuids": ["4d8a29ea-eef5-5d19-ae9f-edd364c5062b"]
                            },
                            "xValue": -43,
                            "xUnit": "VW",
                            "yUnit": "PX",
                            "zUnit": "PX"
                        }
               `
               .
               .
               .
               .
               .
               .
               .
               .
               .
               .
               `
                }]
            }],
            "createdOn": 1601117338701
        },
```


# 2 Click Event
If Scrolling event use Next number (previousEventNumber+2)
```javascript
{
"e-6"{
        .
        .
        .
},

"[Event Number] (e-8) ": {
            "id": "[Event Number] (e-8)",
            "name": "",
            "eventTypeId": "MOUSE_CLICK",
            "action": {
                "id": "",
                "actionTypeId": "GENERAL_START_ACTION",
                "config": {
                    "delay": 0,
                    "easing": "",
                    "duration": 0,
                    "actionListId": "[ACTION ID]",
                    "affectedElements": {},
                    "playInReverse": false,
                    "autoStopEventId": "e-9"
                }
            },
            "mediaQueries": ["main", "medium", "small", "tiny"],
            "target": {
                "appliesTo": "ELEMENT",
                "styleBlockIds": [],
                "id": "[jay01.webflow.io]|60c5db70-5889-8897-3488-c17c50d26c87"
            },
            "targets": [],
            "config": {
                "loop": false,
                "playInReverse": false,
                "scrollOffsetValue": null,
                "scrollOffsetUnit": null,
                "delay": null,
                "direction": null,
                "effectIn": null
            },
            "createdOn": 1601178079741
        },}
```