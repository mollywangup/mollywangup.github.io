- [What is Android Debug Bridge (ADB)?](#what-is-android-debug-bridge-adb)
- [How to install ADB on macOS, Linux, and Windows](#how-to-install-adb-on-macos-linux-and-windows)
  - [macOS](#macos)
  - [Windows](#windows)
  - [验证安装](#验证安装)



# What is Android Debug Bridge (ADB)?
官方文档: https://developer.android.com/studio/command-line/adb
用途: 安卓debug命令行工具

# How to install ADB on macOS, Linux, and Windows
## macOS
使用macOS常用的包管理器 [Homebrew](https://docs.brew.sh/Installation) 安装
```shell
brew install android-platform-tools
```
## Windows
手动下载安装压缩包，地址：[SDK Platform Tools release notes](https://developer.android.com/studio/releases/platform-tools#downloads)

添加到系统环境变量：https://www.cnblogs.com/handsomefa9527/articles/13030403.html


## 验证安装
```shell
adb --version
```

