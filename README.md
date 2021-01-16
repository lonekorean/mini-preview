# mini-preview

jQuery plugin for adding live mini-previews to links on hover.

Check out [the demo](https://lonekorean.github.io/mini-preview/) to see how it looks.

## Usage

Make sure you include both the CSS and JS files on your page.

Bind MiniPreview to a link like this:

	$('a').miniPreview({
		width: 256,
		height: 144,
		scale: .25,
		prefetch: 'pageload'
	});

The previous example specifies all the default values. If you're fine with those, you can leave them out and just do this:

	$('a').miniPreview();

Take a look at `index.html` for example working code.
