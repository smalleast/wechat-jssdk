# wechat-jssdk
> Wechat jssdk.


## resources:
+ https://mp.weixin.qq.com/wiki/7/aaa137b55fb2e0456bf8dd9148dd613f.html
+ https://mp.weixin.qq.com/wiki

## based on wx1.2.0
```javascript
!function (a, b) {
  if (typeof module !== 'undefined' && module.exports) {
    module.exports = b(a);
  } else {
    "function" == typeof define && (define.amd || define.cmd) ? define(function () {
        return b(a)
      }) : b(a, !0)
  }
}(window, function (a, b) {
    //wx source code....
})
```

## usage:
+ install from github:
```bash
npm install afeiship/wechat-jssdk --save
```
+ import jssdk
```javascript 1.8
import wx from 'wechat-jssdk';
```

## todos:
- [ ] todo list..
