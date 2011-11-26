BOOST enhanced boilerplate framework
======================================

**BOOST** is a Boilerplate framework that's kind of a best of everything that I find useful. There's a responsive grid, form styling and many other useful bits and pieces. Basically, it's a blend of @h5bp, '320 and up' by @malarkey, @inuitcss, formalize.me by @nathansmith & Skeleton by @dhgamache - you guys rock!


Let's get started
-----------------

**BOOST** uses the 'mobile-first' methodology & to find out more, please read the excellent post 'Mobile First' by Luke Wroblewski at http://www.lukew.com/ff/entry.asp?933


## CSS
26/11/2011 - Fairly major update: Separated boost.css into component parts for better manageability

### app.css
For your website's page-specific styles (Use this file 2nd last in your source)

### typography.css
For your website's typography styles

### globals.css
Include this if you want to use the 1kb grid from http://1kbgrid.com

### ui.css
Buttons, Alerts, Notices/Alerts, Tabs, Pagination, Lists, Panels

### forms.css
Mostly styles from http://formalize.me with a small amount from Inuit & a bunch from me!

### tools.css
Non-semantic helper classes & Print styles (Use this file last in your source)

### grids/1kbgrid.css
Include this if you want to use the 1kb grid from http://1kbgrid.com

### grids/zurbgrid.css
Include this if you want to use the grid from Zurb's Foundation framework http://foundation.zurb.com/

### grids/inuitgrid.css
Include this if you want to use the Inuit grid

### grids/tinyfluidgrid.css
Include this if you want to use the Tiny Fluid Grid from http://www.tinyfluidgrid.com/

### grids/nogrid.css
Include this if you do not want to use one of the grids provided & would like to use your own

### handheld.css
Straight from the HTML5 Boilerplate

## HTML
1.	Mixture of '320 and up' & HTML5 Boilerplate.
2.	example.html has almost every element

## Javascript

### script.js
Fix for orientation change glitch in iOS


### Polyfills
1.	imgsizer.js - better responsive images in Internet Explorer (Find out more: http://unstoppablerobotninja.com/entry/fluid-images/)
2.	dd_belatedpng.js - transparent png support in IE6