# 解题思路

回文 指的是`上海自来水来自上海`这样正这反着都是一样的。

## 思路1
对于数字来说，可以利用数字的的特性，进行翻转。
```javascript
// 54/10 = 5.4
var num = Math.floor(54/10);
console.log(54%10);
```