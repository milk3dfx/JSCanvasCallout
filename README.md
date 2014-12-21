JSCanvasCallout
============
```
createCanvasDescriptionCallout(parameters)
```
Function creates canvas with callout image.

## Parameters

* text
* font
* fontSize
* textColor
* textAlign
* maxWidth
* padding
* paddingLeft
* paddingRight
* paddingTop
* paddingBottom
* borderWidth
* borderColor
* backgroundColor
* margin
* pointerSide
* pointerWidth
* pointerStart
* pointerEnd

## Example
```
var cCallout = createCanvasDescriptionCallout({
	text:"Hello!!!",
	fontSize:15,
	textAlign: "center",
	padding:20,
	paddingTop:10,
	borderColor: "#AA5533",
	backgroundColor: "#DDFFEE",
	margin:100, 
	pointerSide:"left",
	pointerStart:0.3,
	pointerEnd: 0.5,
	pointerWidth: 0.2
});
	
document.body.appendChild(cCallout);
```

Copyright 2014 VsReality