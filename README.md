
## flutter ffigen demo

## 生成

```bash
flutter pub run ffigen --config ffigen.yaml
```

## 启动

```bash
$ cd example
$ flutter run
```

## 问题处理

1. [编译缺少报错](https://github.com/dart-lang/native/blob/main/pkgs/ffigen/doc/errors.md)

```
compiler-opts:
  - '-Wno-nullability-completeness'
  - '-Wno-availability'
```
2. [移动ffi到dependencies](https://github.com/flutter/flutter/issues/130103)





## 教程地址
https://codelabs.developers.google.com/codelabs/flutter-ffigen?hl=zh-cn#4