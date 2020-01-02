# vue-native

特点：使用vue语法开发移动端app。`react-native`可用地功能，`vue-native`都可以使用。

核心原理：vue-native是对react-native进行了一层包装。其中通过使用`react-vue`将vue语法进行了translation,转变成了react。

[局限性](https://vue-native.io/docs/index.html)

## 如何启动

> 本项目通过`react-native`提供地cli工具 `npx react-native init noWithExpoVueNative --no-expo`创建,意味着：`For React Native CLI users`

* 方式一:
  命令行执行`yarn start`
  使用 `Expo app`(到官方expo上下载此app，网盘中已存)扫描二维码

* 方式二:
  确保模拟器安装以及已经运行
  命令行执行`react-native run Android`

## 下载安装expo，用于调试

[expo下载方法](https://blog.csdn.net/qq_35414779/article/details/84755028)

1.谷歌浏览器，谷歌应用商店安装插件 `APK Downloader`

2.打开该插件，输入apk下载链接地址 `https://play.google.com/store/apps/details?id=host.exp.exponent`

3.下载即可，手机没有vpn，那么就使用电脑下载后传输到手机上.

## genymotion相关

1. adb devices 无法列出genymotion中启动地设备： 替换platform-tools中三文件，文件已存网盘
2. [genymotion无法联网](https://blog.csdn.net/fesdgasdgasdg/article/details/53907065)