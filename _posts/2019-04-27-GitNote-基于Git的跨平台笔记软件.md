---
layout: post
title: 'GitNote 基于 Git 的跨平台笔记软件'
date: '2019-04-27'
tags:
     - GitNote
author: 'zhaopeng'
---

GitNote 基于 Git 的跨平台笔记软件
为什么
自从工作之后,我开始进行笔记记录,这是一个很棒的习惯.我曾经使用过 EDiary Evernote Onenote Wiz 麦库等,都是一些不错的笔记软件,但是都有一些各式各样的问题,不能满足我的使用.

2013 年,我用 java 编写了第一款笔记软件 jnote,支持 markdown 和富文本编辑器,但是没有云同步功能.
2016 年,我用 electron 和 JavaScript 编写了一个 markdown 编辑器 ndpeditor,不是笔记软件.
2017 年,我用 electron 和 JavaScript 编写了基于 git 的 GitNote 笔记软件,这个采用一个 React开发的版本,这是一个没有发布的版本.
2018 年,我用 Vue重构了 GitNote,更强大的 GitNote.

git 同步
git 是一个很棒的工具,GitNote 支持 git 的全部特性,并且不依赖本地 Git 环境. 你可以使用任何支持 Git 的仓库.

https://github.com/ 免费版支持无限私有仓库
https://BitBucket.com/ 免费版支持私有仓库
https://gitlab.com/ 免费版支持私有仓库
https://gitee.com/ 免费版支持私有仓库(推荐)
https://coding.net/ 免费版支持私有仓库
还有很多

gitnote.png

GitNote 是一款基于 Git 的跨平台笔记软件,内置 git 支持,无须本地有任何 git 环境,拥有 git 的全部特性,可以任意的恢复笔记版本记录,依托 github 的免费不限量私人仓库,你的笔记没有空间的限制,你的数据完全属于你自己.

Todo
轻量级的 todo 管理,在笔记中快速便捷创建 Todo ,没有复杂管理流程,只需要关注完成和未完成.用极简的方式来管理自己的 todo.

todo.png

富文本编辑器
富文本编辑器,不仅支持各种复杂的文字编辑,还支持快捷键、公式、语法高亮、Todo、图片粘贴,等等功能.

html.png

MARKDOWN
不仅是一款漂亮的 markdown 的编辑器,而且还支持编写幻灯片功能,方便你进行幻灯片演讲.

markdown.png

附件
不仅仅支持各种各样的文件作为附件,还能自动识别图片,将图片插入到笔记中.

attachment.png

跨平台
Mac windows Linux 全平台支持,未来也会对移动端进行支持.

os.png

收藏
通过浏览器插件,可以收集网络上面的任何内容,自动同步到你的笔记仓库中.

collection.png

扩展
提供强大丰富的扩展 API,可以自由的定制功能扩展插件,可以为提供思维脑图,番茄工作法,图床等等功能

extension.png

特色插件
思维脑图
支持思维脑图,帮助我们用形象化的方式,科学的处理事情,比如记录和激发创意,并且支持多种导出方式.

kityminder.png

流程图
支持制作流程图，流程图，组织结构图，UML，ER 和网络拓扑图等,并且支持多种导出方式.

grapheditor.png

演示文稿
使用 markdown 可以很容易的创建出 web 版的演示文档,并支持导出.

revealjs.png

多图床
支持多个图床平台上传,自动插入到笔记中,提供 API 可以自由定制自己的图床.

upload.png

官网地址:
[https://gitnoteapp.com/](https://gitnoteapp.com/)

下载地址:
https://gitnoteapp.com/zh/#download