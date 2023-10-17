微信官方 js-sdk
----

说明: 仅将官方 js-sdk 发布到 npm，支持 CommonJS，便于 browserify, webpack 等直接使用。

从 1.6.1 版本开始支持 TypeScript

js源码: https://res.wx.qq.com/open/js/jweixin-1.6.0.js

官方使用说明: https://mp.weixin.qq.com/wiki?t=resource/res_main&id=mp1421141115

安装:
```shell
npm install weixin-js-sdk
```

使用:
```javascript
// commonjs
var wx = require('weixin-js-sdk');

// es module
import wx from 'weixin-js-sdk'
```

### Old versions

* [1.0.0](https://github.com/yanxi-me/weixin-js-sdk/tree/1.0.0)
* [1.2.0](https://github.com/yanxi-me/weixin-js-sdk/tree/1.2.0)

### 感谢

TypeScript 定义文件来自 [wx-jssdk-ts](https://github.com/zhaoky/wx-jssdk-ts/blob/master/index.d.ts)
