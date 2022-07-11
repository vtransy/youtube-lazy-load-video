# youtube-lazy-load-video
Lazy load youtube video until user click on video to watch. This helps optimize speed of site


This project clone from https://www.cssscript.com/load-youtube-video-needed-lazyload/ with updated code
Original link: https://github.com/the-muda-organization/youtube-lazyload



Template for Youtube video container


Load the Youtube LazyLoad’s JavaScript and CSS files in the html.

```<link href="yoututbe-lazyload.min.css" rel="stylesheet">
<script src="youtube-lazyload.min.js">```
  
  
Create an empty container for the Youtube video and specify the video ID in the data-id attribute:
<div class="yt-lazyload" data-id="SACu6d2pdOI"></div>
  
  
Customize the color of the Youtube logo. 0=none, 1=black, 2=color-black, 3=white, 4=color-white
`<div class="yt-lazyload" data-id="SACu6d2pdOI" data-logo="1"></div>`
  
  
Customize the thumbnail to fetch.

`<div class="yt-lazyload" data-id="SACu6d2pdOI" data-thumb="1"></div>`
