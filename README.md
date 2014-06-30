# Responsive Full Background Image Using CSS
[![Responsive Full Background Image](http://cdn.sixrevisions.com/0431-02_responsive_background_demo_ss.jpg)](http://sixrevisions.com/css/responsive-background-image/)

## Demo
View the [demo on Six Revisions](http://cdn.sixrevisions.com/0431-01_responsive_background_image_demo/responsive-full-background-image-demo.html).

## What Is This?
These are the sources files for a Six Revisions tutorial called [Responsive Full Background Image Using CSS](http://sixrevisions.com/css/responsive-background-image/).

* `responsive-full-background-image.css` - this contains the CSS for achieving the responsive full background image
* `responsive-full-background-image-demo.html` - this is the HTML source code
* Files in the `/presentational-only` are not required. They're purely for demonstrative purposes.
* `/images` directory contains the background images. The background image is from [Unsplash](http://unsplash.com/).

## Basics
The most important property/value pair is `background-size: cover`, which dynamically scales the background image to cover the viewport even when it's resized. Responsive full background image can be achieved using this simple style rule:

```
background: url(background-photo.jpg) center center cover no-repeat fixed;
```

For a faster page load on small screens (i.e., mobile devices) a scaled-down version of the background image is served using a media query.

For a complete explanation, read this tutorial: [Responsive Full Background Image Using CSS](http://sixrevisions.com/css/responsive-background-image/).

## License
The source code is released into the public domain under [CC0 1.0 Universal](https://github.com/sixrevisions/responsive-full-background-image/blob/master/LICENSE). The source code is free of any copyright restrictions. You can use, copy, sell, modify, distribute, etc. the code, even for commercial purposes, all without asking permission, providing attribution or performing any requirement.
