# DOUAudioStreamer 使用的例子
本例子，介绍如何使用[DOUAudioStreamer](https://github.com/douban/DOUAudioStreamer)播放，本地和网络的MP3文件，

![douPlayer](douPlayer.jpg)

## tips

* 在DOUMPMediaLibraryAssetLoader的.h和.m文件中的开头和结尾， 注释掉或删除 
`#if TARGET_OS_IPHONE 和 
`#endif

* DOUSimpleHTTPRequest.m文件中加入
`#import &lt;ltUIKit/UIKit.h&gt;

* 本地文件是秒速5cm预告片的BGM。[我曾经也弹过的](https://www.youtube.com/watch?v=CScTeU065dA)




