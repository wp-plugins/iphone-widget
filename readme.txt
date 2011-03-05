=== iPhone-Widget ===
Contributors: vickio & Raging Kitty (adapted by Raging Kitty from the Simple Image Widget by vickio)
Donate link: http://www.kittyridge.com/freebies/
Tags: image, sidebar, widget, photo, picture, book, cover, iPhone, 2, ereader, ebook, book, read, novel, apple, mac
Requires at least: 2.5
Tested up to: 2.9.2
Stable tag: 1.2

The simple way to show what your reading on your iPhone or e-reader.

== Description ==

Using this widget you can easily place the iPhone containing an image of the cover of the book you are reading in the sidebar. You can also specify a URL to link to when clicking on the book cover image. Supports multiple instances, so you can use it multiple times in multiple sidebars. (adapted from the Simple Image Widget)

Once the plugin is enabled, the widget will be available in your widgets list as "iPhone Widget". You can add this widget to sidebars as many times as you need. The control interface allows you to specify the following options for each instance of the widget:

* Image URL: The full URL to the image file
* Alternate Text: Shown by the browser if image cannot be displayed
* Link URL: URL to open when the book cover image is clicked on (optional)
* Open link in new window: If this is checked, the above link URL will open in a new browser window

== Installation ==

Installation is very simple:

1. Copy/upload the `iPhone-Widget` folder to your `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Add the "iPhone Widget" plugin to a sidebar in 'Design' -> 'Widgets'

== Frequently Asked Questions ==

= How do I upload an image? =

The iPhone Widget does not provide a mechanism for uploading images or files. You can however upload an image in the 'Write' section of WordPress. From there you can click on the 'Add an Image' icon (next to 'Add Media' label). After uploading an image, copy the 'Link URL' for use in your iPhone Widget.

= How many images can be display? =

Each instance of the widget can only display one image, but you can create as many instances as you need.

= How do I change the alignment? =

This can be done with CSS.  Depending on your WordPress theme, one of these methods below will work, though you may have to experiment a little to find out which one.

For the last one with margin top, right, bottom, and left, replace the 0's with a number, for example 10px, where the px stands for pixels.  As you increase or decrease a side, the Ereader will shift position enabling you to get the perfect spacing in you sidebar.  Don't forget that you can use negative numbers too, like -10px.  Experiment with the numbers and refresh your website to see what way the Ereader moves in your sidebar.  Keep doing this until its just right!) :

`.iphone { text-align: center; }
.iphone { margin:0 auto; }
.iphone { margin:0 auto; text-align: center; }
.iphone { margin:0 auto; text-align: left; }
.iphone { margin-top:0px; margin-right:0px; margin-bottom:0px; margin-left:0px; }`

== Screenshots ==

1. iPhone Widget control interface
2. iPhone Widget in sidebar
