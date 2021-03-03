# 逐行阅读vue2的源代码
## vue2.6目录
从vue官方拷贝来的2.6正式版，在vue2.6中开启sourceMap,

```js
// 目录：vue-2.6\scripts\config.js
// line 241: sourceMap: true
```

运行npm run dev, 动态打包开发版。

## demo文件夹
demo文件夹是业务代码， 引用了vue2.6内部的入口。

```js
import Vue from '../../dist/vue'
```

## 如何启动

```dash
cd demo
npm i
npm run serve
```

## 如何阅读源码?
在demo/src中写业务代码, 在vue-2.6目录中打断点, 逐行分析.


