<!-- ![header](http://nano-assets.gopagoda.io/readme-headers/nanobox-dashboard-svg-lib.png)

## Installation
```
bower install nanobox-core/svgs-dashboard-nano --save
```

## Local Dependencies
```
rel/nanobox-dashboard.css
rel/nanobox-dashboard.js
```

![key](http://shots.delorum.com/client/view/Screen%20Shot%202015-06-01%20at%2010.47.26%20AM.png)
 -->

##Usage
```jade
img.shadow-icon(data-src="badge-ruby")
img.shadow-icon(data-src="badge-nodejs")
img.shadow-icon(data-src="badge-python")
img.shadow-icon(data-src="badge-php")
img.shadow-icon(data-src="badge-scala")
img.shadow-icon(data-src="badge-go")
img.shadow-icon(data-src="badge-elixir")
img.shadow-icon(data-src="badge-java")
img.shadow-icon(data-src="badge-erlang")
img.shadow-icon(data-src="badge-clojure")
img.shadow-icon(data-src="badge-lua")
img.shadow-icon(data-src="badge-c")
img.shadow-icon(data-src="badge-rust")
img.shadow-icon(data-src="badge-perl")
img.shadow-icon(data-src="badge-lisp")
img.shadow-icon(data-src="badge-none")
img.shadow-icon(data-src="logo-horizontal")
```

This must be called after the page has loaded:
```coffeescript
shadowIcons = new pxicons.ShadowIcons()
# Pass in the jquery html element to search for .shadow-icon img tags.
shadowIconsInstance.svgReplaceWithString pxSvgIconString, $("body")
```
