# Build
* Download progressCircle.js and just add it to your project
```
//Add it before your scripts
<script src="ProgressCircle.js"></script>

```
 
# Run Circles
* Create new ProgressCircle
```
const myBrandNewCircle = new ProgressCircle(canvas, duration, progress, size, sizeMid, color, colorMid, font, alpha);
```
# Parameters
* example
```
//create canvas, make it canvas.width = canvas.height; to get circle shape, and pass it as a first parameter, set(canvas element).
canvas = document.querySelector(".yourCanvas"),

//duration in frames number, -> 60fps, set(0-max number).
duration = 70,

//progress of your circle set (1 - 0). it's mean: 100%-0%.
progress = .80,

//size of your circle set (1 - 0). it's mean: 100%-0%.
size= .15,

//sizeMid is a background circle width. Its realative to "size", set (1 - 0). it's mean: 100%-0%.
sizeMid = .33, //sizeMid = size * sizeMid  

//color of the progress circle, set(string).
color = "red",

//colorMid is a backgroud circle color, set(string).
color = "rgba(1,1,1,.5)',

//font, font style, set (string)
font = "Arial 20px bold",

//alpha, aplha for all circleProgress object set(0 -1).
alpha = 1;

```
