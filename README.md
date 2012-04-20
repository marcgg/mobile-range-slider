# Mobile Range Slider 
## A Touch Slider for Webkit / Mobile Safari

This lightweight JavaScript range slider works on mobile devices such as iOS or Android without any dependencies such as jQuery.

### Basic Usage

```js
new MobileRangeSlider('slider'); // passing an ID
new MobileRangeSlider(element); // passing a DOM element
```

### Advanced Usage

```js
var slider = new MobileRangeSlider('slider', {
  min: -50,
  max: 50,
  value: 0,
  change: function(value){
    console.log(value);
  }
});

...

slider.setValue(25);
```

### Options

* `min` - minimum value. Default: 0
* `max` - maximum value. Default: 100
* `value` - initial value. Defaul: 0
* `change` - callback handler

---

Developed by [Ubilabs](http://ubilabs.net).