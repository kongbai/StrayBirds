---
layout: default
title: JavaScript学习
---

### JavaScript中的布尔值转化
值得注意的布尔值的转化，一开始还以为空数组，空对象也会返回false，结果我错了！长见识了！
---javascript
Boolean(undefined);//输出false
Boolean(null);//输出false
Boolean(0);//输出false
Boolean(NaN);//输出false

-------------------------------

Boolean([]);//输出true
Boolean({});//输出true
Boolean(function(){});//输出true
Boolean(/sary/);//输出true
---

