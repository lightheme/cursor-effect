![grab-landing-page](effect.gif)

<h4>A cursor effect that creates gasoline blurs, written in pure html, css, and javascript. Uses WebGL to create animations. It is recommended for use on resource-intensive projects, as it may be difficult to draw animations on weak hardware.</h4>
<h4>To add this effect to you project you should download effect.js file and add to you project next code:</h4>

1. **To you html file**:
```html
<canvas id="js-cursor-effect"></canvas>
<script src="effects.js"></script>
```

2. **To you css file**:
```css
html{
    width:100%;
    height:100%;
    scroll-behavior:smooth
}
body{
    margin:0;
    width:100%;
    height:100%;
    background:#0D1117
}
#js-cursor-effect {
    position: fixed;
    height: 100%;
    width: 100%;
    z-index: -1;
    top: 0;
    pointer-events: none;
}
```
