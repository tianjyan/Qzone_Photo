# Deprecated
因为官方登陆的API已经做了变更，加上自己没有太多精力和时间再维护这个库，所以废弃这个库。

# 简介
[![Platform](https://img.shields.io/badge/Language-Python%202.7-blue.svg)](https://www.python.org/)
<!--[![Build](https://api.travis-ci.org/youngytj/Qzone_Photo.svg?branch=master)](https://travis-ci.org/youngytj/Qzone_Photo)
[![Gitter](https://img.shields.io/badge/chat-on%20gitter-blue.svg)](https://gitter.im/tianjyan/Lobby)-->

批量下载QQ空间相册。

目前支持下载的包括：
1. 对所有人公开的相册；
2. 好友中好友可见的相册。

# 使用方法
* 安装[Python 2.7.13](https://www.python.org/downloads/release/python-2713/)；
* 安装依赖：pip install -r requirements.txt；
* 修改配置文件`config.json`
* cmd中键入Python main.py运行。

# 依赖列表
qqlib：https://github.com/gera2ld/qqlib

# 报告Issue
欢迎报告Issue，请确保Issue的描述信息的完整，以下Issue可能无法修复：
* Issue信息描述并未按照模板描述；
* 自行修改代码以后导致的Issue。

# 配置文件参考
| 参数名          | 类型           | 说明          |
|:--------------:|:-------------:|:------------:|
| account        | 必须           | 登录的QQ      |
| password       | 必须           | 登录QQ的密码   |
| target_qq      | 必须           | 下载相册的QQ   |
