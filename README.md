# weixin
微信小程序的开发流程及环境搭建

[开发文档](https://mp.weixin.qq.com)

## 环境搭建

只适用于window mac

1. 下载微信开发工具
2. 在微信开发的设置的开发设置中获取到appId
3. 打开微信开发工具，输入appId创建项目

## 初始化文件架构及说明

### app.js

小程序脚本代码，可以监听小程序生命周期函数，调用丰富的api接口和声明全局变量

### app.json

小程序全局配置文件，包括页面组成（写路径），系统环境下的基本颜色配置。不能写注释

### app.wxss

小程序的公共样式表，后缀为.wxss

## 页面创建

每一次创建页面都需将路径存放在app.json中，每一个小程序页面都是由同名不同后缀的四个文件组成，比如index.wxml,index.wxss,index.js,index.json

### index.wxml

