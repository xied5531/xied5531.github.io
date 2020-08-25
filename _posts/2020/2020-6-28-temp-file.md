---
title: 临时文件，大作用
date: 2020-6-28 14:47:42
tags: 临时文件
---

Q：下载或上传过程中，中间文件无法和正常完整文件区分开来

A：增加临时文件

1. 下载或上传过程中，创建临时文件，例如“完整文件名.part”
2. 下载或上传完成后，重命名文件，“完整文件名.part” -> “完整文件名”

S：避免中间文件影响正常使用。和Chrome浏览器下载时流程类似。