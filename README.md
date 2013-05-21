## scrollchart

Standalone, simple indications of scroll progress. Works great with scroll-based
applications like [pig](http://github.com/tmcw/pig).

### api

`scrollChart.barChart(elem, options)`

draw a bar chart-style visualization of scroll progress.

valid options are:

* fg: foreground fill
* bg: background fill

### example

```html
<canvas id='scroll-chart'></canvas>
```

```css
#scroll-chart {
    position:fixed;
    top:0;
    right:0;
    left:0;
    height:20px;
    width:100%;
    z-index:-10;
}
```

```js
scrollChart.barChart(document.getElementById('scroll-chart'), {
  fg: '#22aa33',
  bg: '#eee'
});
```
