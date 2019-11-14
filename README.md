# Zedna WP Image Lazy Load
Zedna WP Image Lazy Load plugin

Official WordPress plugin can be found on [WordPress plugin repository](https://wordpress.org/plugins/wp-image-lazy-load/)

## Description
Decreasing page load time by progressive loading of images and other elements. They will load just when reach visible part of screen. Lazy loading can be also applied on themes.

Plugin affect these elements:

<img> element

CSS property background-image

responsive images with srcset attribute

<iframe> element

<video> element

## Features:

-reduce up to 90% of page load time, depends on elements amount

-compatible with Visual Composer

-compatible with WooCommerce

-you can choose to skip all iframes or just one in specific element

-you can choose to skip specific elements with some class

-you can show elements earlier or later than are visible on the screen

-optional fade in animation

## Usage outside of WordPress
You can use this plugin even if you don't have a WP site.
Just include `image_lazy_load.js` to your project and change top variables:

```
//get options from DB
	var skipIframe = true; //true=skip iframes
	var skipParent = 'iframeClassOne;iframeClassTwo'; //classes of iframe parent without "." dot
	var skipAllParent = 'firstClass;secondClass'; //classes of elements parent without "." dot
	var skipVideo = false; //true=skip videos
	var loadonposition = 200; //200px above windows bottom edge
```
