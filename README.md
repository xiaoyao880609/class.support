# class.support

Javascript class support

## Getting Started
### In the browser
Download the [production version][min] or the [development version][max].

[min]: https://raw.github.com/cuizuoli/class.support/master/dist/class.support.min.js
[max]: https://raw.github.com/cuizuoli/class.support/master/dist/class.support.js

In your web page:

```html
<script src="js/class.support.min.js"></script>
<script>
Class('class.Support.Test', {
	init: function(options) {
		var _this = this;
		_this._options = $.extend({
			id: 'body'
		}, options);
		_this._root = $(_this._options.id);
		_this._bindEvent();
		//TODO init.
	},
	_bindEvent: function() {
		var _this = this;
		// TODO binding event.
	}
});
new class.Support.Test();
</script>
```
