# Cleaner Youtube
<strong>Change the appearance of embedded Youtube iframes for a cleaner look.</strong>

Simply embed your Youtube video iframe in the usual way and this script will take care of the rest.

## Notes

<strong>Tweak the CSS</strong>

Change the presentation ro suit your website.

<strong>Requires jQuery</strong>

Will only work with <a href="https://code.jquery.com/jquery-1.7.0.min.js">jQuery 1.7.0</a> or higher.

<strong>Only works when there is one video on the page</strong>

This is not ideal I know, but if you only have one video on a page at a time then you're good to go.

<strong>Title is automatically added</strong>

The title is pulled from the <a href="https://noembed.com">noembed.com</a> service. You can pull in more data about the video if desired.

<strong>Image size</strong>

The image size used in this demo is the full resolution thumbmail from Youtube (1280 x 720 in this case). The large size might not be ideal for bandwidth reasons, but you can use a smaller version if desired. See the comments in the code.

<strong>Iframe position</strong>

The iframe must be placed after the script.

<strong>How it works</strong>

A clean interface is constructed with a thumbnail and SVG, wrapped in a container div. Upon clicking anywhere in the div, the image is swapped out with an auto-play version the original Youtube embed iframe.

<img src="demo.gif" />
