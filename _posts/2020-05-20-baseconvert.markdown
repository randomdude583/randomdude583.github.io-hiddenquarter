---
layout: post
title:  "Baseconvert"
date:   2020-05-20 21:03:36 +0530
---
Baseconvert is a Dart package for converting rational numbers from any input base to any output base.



```javascript
// base(number, {inBase=10, outBase=10, maxDepth=10, string=false, recurring=true})

base([15, 15, 0, ".", 8], inBase: 16, outBase: 10);
--> [4, 0, 8, 0, '.', 5]

base("FF0.8", inBase: 16, outBase: 10, string: true);
--> '4080.5'

base("4080.5", inBase: 10, outBase: 16, string: true);
--> 'FF0.8'
```


[GitHub Repository][github-repo]

[![pub package](https://img.shields.io/pub/v/baseconvert.svg)](https://pub.dev/packages/baseconvert)





[github-repo]: https://github.com/randomdude583/baseconvert


