# Dynaverse

差不多把 [Croquet](https://wwj718.github.io/post/%E7%BC%96%E7%A8%8B/croqueta-collaboration-system-architecture/) 相关的论文都读完了。这是迄今为止我所知道的与 Metaverse 有关最疯狂/伟大的想法。

开始着手组建有能力追逐这些目标的团队。

最近在读[《游戏引擎架构》](https://book.douban.com/subject/25815142/)，里头提到「典型游戏团队的结构」，这是导致我写下这则备忘录的主要原因。

## 愿景

在动态媒介(Dynamic Media) 创造出的自由空间里, 人们彼此之间的协作与理解被深度促进

## 使命

构建 互联网规模、深度协作、动态可生长的 Metaverse

## 关于 Dynaverse

>  语词的意义是其使用者共同的观点赋予的  -- 维特根斯坦

我是在个人计算社区的传统背景下使用 `dyna` 一词:

*  Dynabook
*  Dynamic Media
*  dynamic object-oriented programming
*  Dynamicland

已注册域名: `dynaverse.live`

live: live programming

## 团队构成(正在组建中...)
*  图形学 (Teapot)
*  通信协议 (TeaTime)
*  引擎设计
*  3D 建模
*  创意
*  写作
*  ...

欢迎你的加入！

我们希望团队成员深入个人计算(Personal Computing)的历史(Smalltalk/Alan Kay 是很好的入口)，深入了解 [Croquet](https://wwj718.github.io/post/%E7%BC%96%E7%A8%8B/croqueta-collaboration-system-architecture/) 项目。

我们期待你是以下项目(之一)的狂热爱好者:

*  Smalltalk
*  图形学
*  LISP

## 基础工作
*  Squeak/Smalltalk
   *  [Morphic](http://wiki.squeak.org/squeak/morph)
      *  递归渲染树
   *  [Croquet](https://wwj718.github.io/post/%E7%BC%96%E7%A8%8B/croqueta-collaboration-system-architecture/)
      *  Teapot
         *  半保留的模型(semi-retained model)
         *  对象是递归的计算机，每个对象都保留完全访问 OpenGL 库的能力
      *  TeaTime
         *  复制版本对象(replicated versioned objects)
         *  同步事件而不是状态
*  Qwaq 源码
*  Lively
   *  在浏览器环境里构建 live programming 环境
*  OMeta/Ohm
   *  脚本语言(Python/JavaScript/Lua/Smalltalk)
*  WebGPU/WebGL/WebAssembly/...
*  《游戏引擎架构》

## 与主流的交叉点
*  OpenXR
*  glTF
*  Blender
*  threejs/aframe
*  ...

## Logo

考虑以下元素

*  梯子画云
*  齿轮与细胞

<img width=350 src="https://www.codelab.club/img/8e7dc0768797cfa0fa044a407cbc0bd1.png" />


<img width=500 src="https://adapter.codelab.club/img/003610-scaling-computers.jpg" />

## 推荐阅读

*  [[译]AR/VR 为何将获胜？它将如何获胜为何重要？](https://wwj718.github.io/post/%E7%BC%96%E7%A8%8B/why-ar-will-win/)
*  [[译]Croquet: 一个协作系统架构](https://wwj718.github.io/post/%E7%BC%96%E7%A8%8B/croqueta-collaboration-system-architecture/)
*  [[译]Smalltalk背后的设计原则](https://wwj718.github.io/post/%E7%BC%96%E7%A8%8B/design-principles-behind-smalltalk/)
*  [Croquet Programming 1.0B](https://wwj718.github.io/post/img/Croquet%20Programming%201.0B.pdf)
   *  这本册子目前在互联网上找不见了，我在[archive.org](https://archive.org/)里找到的。有我的阅读笔记
*  [wikipedia Croquet Project](https://en.wikipedia.org/wiki/Croquet_Project)
*  [A Computer for Children of All Ages](https://www.mprove.de/visionreality/media/Kay72a.pdf)
*  [Personal Dynamic Media](http://www.newmediareader.com/book_samples/nmr-26-kay.pdf)
*  [Personal Computing](https://mnielsen.github.io/notes/kay/Personal_Computing_1975.pdf)
*  [Squeak Etoys Authoring & Media](http://www.squeakland.org/content/articles/attach/etoys_n_authoring.pdf)
*  [A world of active objects for work and play: the first ten years of lively](https://dl.acm.org/doi/10.1145/2986012.2986029)
*  [dynamicland-501c3-narrative](https://dynamicland.org/dynamicland-501c3-narrative.pdf)
*  [The Early History Of Smalltalk](http://worrydream.com/EarlyHistoryOfSmalltalk/)
*  [Back to the future: the story of Squeak, a practical Smalltalk written in itself](https://www.vpri.org/pdf/tr1997001_backto.pdf)
*  [worrydream refs](http://worrydream.com/refs/) 中与 Kay、Smith、Sutherland 相关的论文
*  [Naming and Synchronization in a Decentralized Computer System](http://worrydream.com/refs/Reed%20-%20Naming%20and%20Synchronization%20in%20a%20Decentralized%20Computer%20System.pdf): TeaTime协议的源头
*  [《雪崩》](https://book.douban.com/subject/3816895/): Metaverse概念的来源

## 参考项目
*  [croquet-squeak](https://github.com/NikolaySuslov/croquet-squeak)
   *  [open-croquet-for-squeak-6](https://blog.krestianstvo.org/en/open-croquet-for-squeak-6/)
*  [wikipedia open cobalt](https://en.wikipedia.org/wiki/Open_Cobalt)
*  [krestianstvo.org](https://www.krestianstvo.org/sdk3)
*  [Tref](3dicc.com)
*  [croquet.io](https://croquet.io/)
*  [hubs](https://github.com/mozilla/hubs)

## FAQ

### 在哪儿讨论？
[github issue](https://github.com/wwj718/Dynaverse/issues)


### 目前的项目状态是怎样的？

还处在准备阶段，我目前致力于梳理出相关资料，感兴趣的同伴可以据此起步。

希望围绕 Alan Kay、Smith... 过去的工作，形成一个有深度的讨论社区。 Alan Kay 将他的大部分工作成果，都归源于当时他所处的那个讨论团体。

### 你目前在做什么？

我目前在写一篇文章《Dynaverse: A Metaverse for Children of All Agess》, 向 Alan Kay 在 1972 年写的 [A Computer for Children of All Ages](https://www.mprove.de/visionreality/media/Kay72a.pdf) 致敬。

首先，致力于勾勒出愿景，描述在这个想象的世界中，人们如何生活、学习、娱乐、工作、创造...

之后，讨论为了实现以上场景，需要设计怎样的体系架构。 论述为何当前的技术是足以实现它的，为何现在是合适的时机。

最后，做出成本预估。


### 如何入门Smalltalk
一些推荐资料:

*  [Smalltalk 入门导览](https://wwj718.github.io/post/%E7%BC%96%E7%A8%8B/smalltalk-guide/)
*  [TheCuisBook](https://cuis-smalltalk.github.io/TheCuisBook/)


### 如何阅读 Croquet 源码

简易以建构主义式的学习方法(Smalltalk的设计深受其影响)

去跟对象(Objects)玩耍，把它们看作你房间里的玩具，推一推它，堆在一起试试...

目前的文档不多([Croquet Programming 1.0B](https://wwj718.github.io/post/img/Croquet%20Programming%201.0B.pdf)几乎是仅有的)，可以通过测试(tests)代码去理解对象。
