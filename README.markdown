# 说明 #
ABPlayer的1.0.11版本以及后续版本将不支持Flex 3 SDK 转为使用Flex 4 SDK。

# Introduction #
ABPlayer is a video player developed in the Flex 3 SDK. It allows users to send comments onto the playing timeline while playing online video. Comments are scrolled across the screen when the video reaches the timeline position of the comment allowing interactive and realtime commenting of the video. It also features bottom, top,positioned and reverse scroll options, that allow users to create closed captioning and subtitles for video. Comments support color, font, size and opacity and can have effects as well.

## Compiling ##
ABPlayer is based on the Flex 3.2 SDK, you can compile this in Flash Builder 4.5 by setting the SDK to the older SDK. The css needs to be modified to use the MX namespace as the project doesn't incorporate Spark components.

## Translations ##
ABPlayer is by default, offered in Chinese (Simplified), you may directly edit strings to translate into any language you wish. Though some English fonts are not completely approprate for positioned comments. If you wish to open 
high level comments to users, you should use a monospace font available cross-platform.

## 中文 ##
ABPlayer是一个Flex 3 SDK/Flex 4 SDK下开发的弹幕播放器，它有着不同于MukioPlayer和PADPlayer的一些特性，也兼容了两个播放器的很多优点。ABPlayer有比较高的可扩展性，也是少数在Flex SDK 3 下提供的全方位弹幕播放器。
ABPlayer支持滚动弹幕，顶部/底部弹幕，逆向弹幕和高级定位弹幕，并且支持渐变，色彩和字体。弹幕可以设置透明度，并且有一系列高级的过滤器（弹幕对象过滤），同时默认包含一些视频的透镜。它支持一系列JS扩展功能，包括动态载入视频/切换分P等等。

此工程为中文工程，有需求的开发者可以自行Checkout。

## Licensing/版权声明 ##
See 'LICENSING' file 