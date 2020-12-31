---
title: Dart入門
description:
date: 2020-12-31
tags:
  - dart
layout: layouts/post.njk
---
dartに入門した。flutterではなく、dartのみ。

## インストール方法
``` bash
$ brew tap dart-lang/dart
$ brew install dart
```

## 使用バージョン
``` bash
$ dart --version
Dart SDK version: 2.10.4 (stable) (Wed Nov 11 13:35:58 2020 +0100) on "macos_x64"
```

## フィボナッチ数
フィボナッチ数とstring interpolationの例。
``` dart
int fibonacci(int n) {
  if (n == 0 || n == 1) return n;
  return fibonacci(n - 1) + fibonacci(n - 2);
}

void main() {
  var ans = fibonacci(20);
  print('fib(20)=${ans}');
}
```

https://github.com/mur6/LearnCompLangs/blob/develop/Dart/examples/fibonacci.dart

## 参考サイト
公式サイト: https://dart.dev/samples
