---
title: 关于Android开发的体会，包括Tauri和其它框架的体验
date: 2026-01-20 19:31:15
tags:
---

# 环境

* Debian 13
* Android Studio + Android SDK 24(mim) + Android SDK 36(target) + Android NDK + CMake
* Rust 1.92.0
* Nodejs 24 LTS
* Tauri2 (js, npm, vanilla)

# Tauri

## 缺点

1. 编译比机械硬盘写入1PB数据还tm慢
2. Rust太诡异了
3. 系统的WebView太诡异了
4. (Rust的缺点) Linux安装太诡异了，命令安装不了，开代理也一样，下载tar.xz归档包安装上结果没rustup，tauri又要rustup添加android架构

## 优点

0. 没看出来有啥优点

# Cordova

## 缺点

1. 配置比较繁琐，还有各种奇葩问题（比如死活访问不了网络）

## 优点

1. 手机用Termux也能构建（比Rust快一亿倍，没那么慢）
2. 老牌稳定
3. npm包，前端框架兼容好
4. 开发体验不错

# Android 原生WebView

## 缺点

1. 新手可能不会写一个WebView的activty
2. 创建Empty Activty项目强制使用Kotlin（如果不会的话算缺点）
3. 可能有一些奇怪的问题
4. Android Studio没中文
5. 必须挂梯（大概不算缺点）

## 优点

1. 原生开发，性能好
2. 使用Kotlin
3. Android Studio好操作，基本点点就能配置好环境（如果看得懂English的话）

# 总结

~~水太深，新手把握不住~~

# 温馨提示

**千万不要在没有卸载之前的一个版本前就安装相同包名相同名称相同版本的不同功能的APK！！！**
**千万不要在没有卸载之前的一个版本前就安装相同包名相同名称相同版本的不同功能的APK！！！**
**千万不要在没有卸载之前的一个版本前就安装相同包名相同名称相同版本的不同功能的APK！！！**

