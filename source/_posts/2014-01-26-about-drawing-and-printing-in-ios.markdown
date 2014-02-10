---
layout: post
title: "About Drawing and Printing in iOS"
date: 2014-01-26 14:50:18 +0800
comments: true
categories: 
---

#At A Glance

    iOS原生的绘画系统包括三个主要的技术：UIKit, Core Graphics, Core Animation。UIKit提供views和在views中high-level绘画方法，
Core Graphics提供在UIKit views中补充的（lower-level）绘画支持, Core Animation 提供UIKit view转化(transformations)和动画(animation)的能力。
Core Animations也负责view的组成。

##Custom UI Views Allow Greater Drawing Flexibilty
    这个文档描述怎样通过原生绘画技术自定义UI, 这些技术（Core Graphics和UIKit frameworks)支持2D绘制。


#Drawing with Quartz and UIKit
    Quartz 是ios中原生绘画技术的名字。The Core Graphics framework是Quartz的核心，
是绘画内容的主要接口。提供以下绘画内容和功能：

＊Graphics contexts

*Paths

*Images and bitmaps

*Transparentcy layers

*Colors, pattern colors, and color spaces

*Gradients and shadings

*Fonts

*PDF content

##Configuring the Graphics Context

##Creating and Drawing Paths

