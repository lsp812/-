LeftRightSlider
===============

/* ***********************************************************

add by jimple

在原作（  https://github.com/heroims/LeftRightSlider  ）基础上进行了如下修改：

1、左右滑开时，主视图添加了一个半透明的遮罩。

2、修改了代码，现在可以在主视图添加一个正常的UINavigationController了。

3、增加 canMoveWithGesture 属性，方便外部停用左右滑动功能。

4、增加对left/right视图的检测，这样当一开始没有设置左/右视图时，对应滑动打开自动屏蔽不可用。


以下是原作的说明，非常感谢作者 @heroims 

*********************************************************** */







![Screenshot1](http://i.imgur.com/N6q2Uk8.gif "Screenshot1") 
![Screenshot2](http://i.imgur.com/98Gwauw.gif "Screenshot2")


网易 ios7 左右拉动框架

把LRNavigationController文件夹和LeftRightSlider文件夹拖入项目即可，支持arc和非arc

LeftRightSlider文件夹为左右滑动框架

LRNavigationController文件夹为视差推出框架

## Minimum Requirement
iOS 5.0

## Installation

### via CocoaPods
Install CocoaPods if you do not have it:-
````
$ [sudo] gem install cocoapods
$ pod setup
````
Create Podfile:-
````
$ edit Podfile
platform :ios, '5.0'
pod 'LRNavigationController',  '~> 1.0.0'
pod 'SliderViewController',  '~> 1.2.0'
$ pod install
````
Use the Xcode workspace instead of the project from now on.

