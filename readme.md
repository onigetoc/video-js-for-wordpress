# HTML5 Video Player for Wordpress 
**Contributors:** onigetoc, nosecreek, Steve Heffernan, schnere  
**Donate link:** http://www.scriptsmashup.com/donation  
**Tags:** html5, video, player, javascript  
**Requires at least:** 2.7  
**Tested up to:** 3.9  
**Stable tag:** 4.5.0  
**License:** LGPLv3  
**License URI:** http://www.gnu.org/licenses/lgpl-3.0.html  

Embed MP4, M4V, OGG, Youtube, WebM, FLV videos in your post or page using HTML5. Self-hosted or CDN hosted responsive HTML5 Video player.  Based on Videojs but updated to the latest version. 5.0+


## Description 

A video plugin for WordPress built on the Video.js HTML5 video player library. Now updated for Videojs 5.0+ with a more beautifull skin. Allows you to embed video in your post or page using HTML5 with Flash fallback support for non-HTML5 browsers. Flash fallback for browser compatibility. Video player for WordPress, built on the widely used Video.js HTML5 video player. 

Compatible with the Wordpress core [video] shortcode and work with the Wordpress insert media button.

Videojs didn't not update their Videojs to 5.0+ for Wordpress and i decided to do it and share it on the Wordpress plugins page.

View [videojs.com](http://videojs.com) for additional information.

* Use the [videojs] shortcode in your post or page using the following options.
* Can use the Wordpress default [video] shortcode.
* Compatible with the old Videojs version.

## Video Pro - Skin builder
Build your own skin with Video Pro, Allo you to create your own skin or use the prebuilds demos skins to start and help you creating you own skin. more infos at: Video Pro skin builder [Video Pro skin builder](http://www.scriptsmashup.com/product/video-pro-skin-builder).
**Demo**: [Video Pro skin builder demo](http://toolurl.com/plugins/videojs-skin-generator-plugin-demo-for-wordpress)


## Installation 

This section describes how to install the plugin and get it working.

1. Upload the `videojs-html5-video-player-for-wordpress` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Use the [videojs] shortcode in your post or page using the following options.


## Screenshots 

### 1. Settings and options
[missing image]

### 2. Basic Skin
[missing image]


##Video Shortcode Options
-------------------------

### mp4
The location of the h.264/MP4 source for the video.
    
    [videojs mp4="http://vjs.zencdn.net/v/oceans.mp4"]

### ogg
The location of the Theora/Ogg source for the video.

    [videojs ogg="http://vjs.zencdn.net/v/oceans.ogg"]

### webm
The location of the VP8/WebM source for the video.

    [videojs webm="http://vjs.zencdn.net/v/oceans.webm"]
    
### youtube
The location of the YouTube source for the video.

    [videojs youtube="https://www.youtube.com/watch?v=mcixldqDIEQ"]

### poster
The location of the poster frame for the video.

    [videojs poster="http://vjs.zencdn.net/v/oceans.png"]

### width
The width of the video.

    [videojs width="640"]

### height
The height of the video.

    [videojs height="264"]

### preload
Start loading the video as soon as possible, before the user clicks play.
Use 'auto', 'metadata', or 'none'. Auto will preload when the browser or device allows it. Metadata will load only the meta data of the video.

    [videojs preload="auto"]

### autoplay
Start playing the video as soon as it's ready. Use 'true' or 'false'.

    [videojs autoplay="true"]

### loop
Causes the video to start over as soon as it ends. Use 'true' or 'false'.

    [videojs loop="true"]

### controls
Use 'false' to hide the player controls.

    [videojs controls="false"]

### muted
Use 'true' to initially mute video.

    [videojs muted="true"]
        
### id
Add a custom ID to your video player.

    [videojs id="movie-id"]
    
### class
Add a custom class to your player. Use full for floating the video player using 'alignleft' or 'alignright'.

    [videojs class="alignright"]

### Tracks
Text Tracks are a function of HTML5 video for providing time triggered text to the viewer. To use tracks use the [track] shortcode inside of the [video] shortcode. You can set values for the kind, src, srclang, label, and default attributes. More information is available in the [Video.js Documentation](http://videojs.com/docs/tracks/).

    [videojs][track kind="captions" src="http://vjs.zencdn.net/v/oceans-captions.vtt" srclang="en" label="English" default="true"][/videojs]

### All Attributes Example

    [videojs mp4="http://vjs.zencdn.net/v/oceans.mp4" ogg="http://vjs.zencdn.net/v/oceans.ogv" webm="http://vjs.zencdn.net/v/oceans.webm" poster="http://vjs.zencdn.net/v/oceans.png" 
	preload="auto" autoplay="true" width="640" height="264" id="movie-id" class="alignleft" controls="false" muted="true"][track kind="captions" src="http://example.com/path/to/captions.vtt" srclang="en" label="English" default="true"][/videojs]
	
### Compatible with Wordpress core video shortcode
The location of the h.264/MP4 source for the video.
    
    [video mp4="http://vjs.zencdn.net/v/oceans.mp4"]
    

##Video.js Settings Screen
--------------------------
The values set here will be the default values for all videos, unless you specify differently in the shortcode. Uncheck "Use CDN hosted version?" if you want to use a self-hosted copy of Video.js instead of the CDN hosted version. *Using the CDN hosted version is preferable in most situations.*

If you are using a responsive WordPress theme, you may want to check the *Responsive Video* checkbox.

Uncheck the *Use the [video] shortcode?* option __only__ if you are using WordPress 3.6+ and wish to use the [video] tag for MediaElement.js. You will still be able to use the [videojs] tag to embed videos using Video.js.



## Changelog 


### 5.0 

* Updated to use Video.js 5.4.6
* Fluide videos
* Remove useless CSS


### 1.0 

* First release.