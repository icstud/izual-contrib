# wukong-robot

wukong-robot 是一个简单、灵活、优雅的中文语音对话机器人/智能音箱项目，目的是让中国的 Maker 和 Hacker 们也能快速打造个性化的智能音箱。

wukong-robot 还可能是第一个开源的支持[脑机唤醒](/bci)的智能音箱。

## 特性

![wukong-robot的特性](https://hahack-1253537070.file.myqcloud.com/images/wukong-docs/wukong-robot-mindmap.png?version=20191123)

* 模块化。功能插件、语音识别、语音合成、对话机器人都做到了高度模块化，第三方插件单独维护，方便继承和开发自己的插件。
* 中文支持。集成百度、科大讯飞、阿里、腾讯等多家中文语音识别和语音合成技术，且可以继续扩展。
* 对话机器人支持。支持基于 [AnyQ](/anyq) 的本地对话机器人，并支持接入图灵机器人、Emotibot 等在线对话机器人。
* 全局监听，离线唤醒。支持 Muse [脑机唤醒](/bci)，及无接触的离线语音指令唤醒。
* 灵活可配置。支持定制机器人名字，支持选择语音识别和合成的插件。
* 智能家居。支持和 mqtt、[HomeAssistant](/smarthome) 等智能家居协议联动，支持语音控制智能家电。
* 后台配套支持。提供配套后台，可实现远程操控、修改配置和日志查看等功能。
* 开放API。可利用后端开放的API，实现更丰富的功能。
* 安装简单，支持更多平台。相比 dingdang-robot ，舍弃了 PocketSphinx 的离线唤醒方案，安装变得更加简单，代码量更少，更易于维护并且能在 Mac 以及更多 Linux 系统中运行。

## Demo

* Demo视频：ycy-robot 月芽特别定制版
    
<center>
    <iframe src="//player.bilibili.com/player.html?aid=50685517&cid=88726713&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width="80%" height="360px"> </iframe>
</center>

* Demo视频：Google AIY Voice Kit + wukong-robot

<center>
    <iframe src="//player.bilibili.com/player.html?aid=81173082&cid=138922674&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width="80%" height="360px"> </iframe>
</center>

* Demo视频：脑机唤醒

<center>
    <iframe src="//player.bilibili.com/player.html?aid=76739580&cid=131259456&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width="80%" height="360px"> </iframe>
</center>

* 后台管理端Demo 
    - 体验地址：https://bot.hahack.com  （体验用户名：wukong；体验密码：wukong@2019）

## 环境要求 ##

### Python 版本 ###

wukong-robot 只支持 Python 3.x，不支持 Python 2.x 。

### 设备要求 ###

wukong-robot 支持运行在以下的设备和系统中：

* 64bit Mac OS X
* 64bit Ubuntu（12.04 and 14.04）
* 全系列的树莓派（Raspbian 系统）
* Pine 64 with Debian Jessie 8.5（3.10.102）
* Intel Edison with Ubilinux （Debian Wheezy 7.8）
* 装有 WSL（Windows Subsystem for Linux） 的 Windows

## 教学视频

想了解全栈项目 wukong-robot 是怎么开发出来的吗？那就不能错过我们在腾讯课堂NEXT学院的视频课程。

这套视频课程将从零开始，一步步教你如何使用 Python 开发出 wukong-robot 。涉及 Python 的基础语法，以及离线唤醒（KWS）、静音检测（VAD）、语音识别（ASR）、语音合成（TTS）、对话机器人等知识背景的介绍及相关sdk和服务的接入，并在这个基础上如何通过一步步的重构优化，开发出一个灵活可配置的 wukong-robot 。另外，还介绍了如何使用 tornado + twitter bootstrap + jQuery + Ajax 开发后台管理端及前端页面。进阶版中还包括了爬虫技术及 Flask 等技术的相关实战。

* 基础篇：https://ke.qq.com/course/387931?tuin=1b8113f4
* 完整篇：https://ke.qq.com/course/384790?tuin=1b8113f4

## 免责声明

* wukong-robot 只用作个人学习研究，如因使用 wukong-robot 导致任何损失，本人概不负责。
* 本开源项目与腾讯叮当助手及优必选悟空项目没有任何关系。
