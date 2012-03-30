# cssMinMax v0.2 - jQuery Plugin

The cssMinMax polyfill plugin lets you use the new CSS3 min() and max() function in your stylesheets.

## Requirements

* jQuery 1.7+

## Demo

[http://indyarmy.com/cssMinMax/](http://indyarmy.com/cssMinMax/)

## Usage

	$( document ).cssMinMax();

cssMinMax works at the document level and changes every element that has a min() or max() function in it's CSS rule.

## Notes

cssMinMax is very much alpha-quality right now. It has been tested in Firefox 11, Safari 5 and Chrome 18 on OSX Lion. Your mileage may vary.

## Extra Thanks

Thanks to http://www.websanova.com/tutorials/jquery/jquery-plugin-development-boilerplate for providing a great boilerplate I could use for my second jQuery plugin

## Changelog

### v0.2

* removed unnecessary settings and options code from boilerplate
* binds to window resize event
