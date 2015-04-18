# LazyLoad and responsive images

This is an example of **lazy image loading** with **responsive images** and **progressive JPEG** image format.

These best practices about **web performance** were implemented using [LazyLoad](http://verlok.github.io/lazyload/) by [Andrea Verlicchi](http://www.andreaverlicchi.eu).

[**SEE ONLINE DEMO**](http://verlok.github.io/img_srcset_lazyload/)

## Responsive Images

Responsive images are implemented using the `img` tag with the `srcset` and `sizes` attributes, and [picturefill](https://github.com/scottjehl/picturefill) as polyfill for older browsers.

## LazyLoad

Images are loaded only as they enter the viewport through the usage of my [LazyLoad](http://verlok.github.io/lazyload/) script, which supports the `srcset` attribute in addition to the good old `src` attribute.

## Progressive JPEG rendering

Progressive JPEG rendering is guaranteed through the usage of the `show_while_loading` option of my [LazyLoad](http://verlok.github.io/lazyload/) script.