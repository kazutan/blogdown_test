---
title: build_test
author: kazutan
date: '2017-05-18'
slug: build-test
categories:
  - R
tags:
  - R
description: description
draft: no
keywords:
  - key
  - words
topics: topic 1
type: post
from_Rmd: yes
---

ほげほげ。

## ほげほげ

ふがふが。


```r
plot(1:10)
```

![plot of chunk unnamed-chunk-1](/figures/post/2017-05-18-build-test/unnamed-chunk-1-1.png)

## ふがふぁ


```r
head(iris)
```

```
##   Sepal.Length Sepal.Width Petal.Length Petal.Width Species
## 1          5.1         3.5          1.4         0.2  setosa
## 2          4.9         3.0          1.4         0.2  setosa
## 3          4.7         3.2          1.3         0.2  setosa
## 4          4.6         3.1          1.5         0.2  setosa
## 5          5.0         3.6          1.4         0.2  setosa
## 6          5.4         3.9          1.7         0.4  setosa
```

```r
knitr::kable(head(iris))
```



| Sepal.Length| Sepal.Width| Petal.Length| Petal.Width|Species |
|------------:|-----------:|------------:|-----------:|:-------|
|          5.1|         3.5|          1.4|         0.2|setosa  |
|          4.9|         3.0|          1.4|         0.2|setosa  |
|          4.7|         3.2|          1.3|         0.2|setosa  |
|          4.6|         3.1|          1.5|         0.2|setosa  |
|          5.0|         3.6|          1.4|         0.2|setosa  |
|          5.4|         3.9|          1.7|         0.4|setosa  |

