# Node.js

# 1.1. Node.js是什么

* 定义
  + Node.js不是一门语言，不是库，不是架构，是一个JavaScript的运行环境
  + 简单来讲就是Node.js可以解析和执行JavaScript代码，完全脱离浏览器运行。
  + 以前只有浏览器可以解析和执行JavaScript代码，现在Node.js也可以运行JavaScript代码

* 浏览器中的JavaScript

  + EcmaScript
    + 基本语法
    + if
    + var
    + function
    + objectArray
    + 等等

  + BOM
  + DOM

* 构建与Chrome的V8引擎上

  + 代码只是具有特定格式的字符串而已
  + 引擎可以认识它，引擎可以帮助去解析和执行代码
  + Google Chrome 的V8引擎是目前公认的解析执行JavaScript最快的引擎
  + Node.js的作者把Google Chrome中的V8引擎移植了出来，开发了一个独立的JavaScript运行环境

* Nodejs中的JavaScript

  - 没有BOM和DOM,服务端不处理DOM、BOM
  - EcmaScript
  - 在Node这个JavaScript执行环境中，为JavaScript提供了一些服务器级别的操作API
    - 例如文件的读写
    - 网络服务的构建
    - 网络通信
    - http服务器等

# 1.2. Node.js的特性

+ event-driven 事件驱动
+ Non-blocking I/O model 非阻塞模型
+ Lightweight and efficient 轻量和高效

# 1.3. Node.Js 能做什么

+ Web服务器后台
+ 命令行工具
  + npm(node开发的)
  + Git(c开发的)
  + Hexo(node开发的)
  + 。。。

+ 游戏服务器、接口服务器等等
+ 对于前端工程师，接触最多的是命令行工具
  + 使用第三方开发的接口等
  + webpack
  + gulp
  + npm

# 1.4. 预备知识

+ HTML
+ CSS
+ JavaScript
+ 简单的命令行操作
  + cd 
  + dir
  + ls
  + mkdir
  + rm等等
+ 具有服务端开发经验更佳

# 1.5. 一些资源

+ Node入门：https://www.nodebeginner.org/index-zh-cn.html
+ 官方API文档：https://nodejs.org/dist/latest-v6.x/docs/api/
+ 中文文档（版本较旧, 可能打不开）： http://www.nodeclass.com/api/node.html
+ 《深入浅出Node.js》
  + 作者朴灵
  + 偏理论和底层，几乎没有业务实战内容
  + 理解底层有帮助
+ 《Node.js权威指南》
  + API讲解
  + 没有业务实战
+ JavaScript标准参考(alpha)：http://javascript.ruanyifeng.com/

+ CNODE社区：http://cnodejs.org
+ CNODE-新手入门：http://cnodejs.org/getstart

# 1.6. 这门课程你能学到啥？

+ B/S编程模型
  + Browser - Server
  + Back-end
  + 任何服务端技术，B/S编程模型概念是一样的，跟语言相通
  + Node只是作为我们学习BS编程模型的一个工具而已
+ 模块化编程
+  异步编程
  + 回调函数
  + Promise
  + async
  + generator
+ Express Web开发框架
+ Ecmascript 6
+ ......
+ 学习Node不仅会帮助大家打开服务端黑盒子，同时会帮助你学习以后的前端高级内容
  + 如 Vue.js
  + React
  + angular等等