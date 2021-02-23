---
title: 将源文件存入github的另外一分支
tags:
  - hexo
categories:
  - hexo
date: 2021-02-23 21:21:59
---



1、在本地将themes目录里面的.git 和.github 全部删除。

2、在blog下，初始化git仓库，并新建分支source，将blog目录下文集存入新分支，添加远程仓库，推送上去。



这样在master分支下保存就是生成博客html文档。而source分支下就是整个博客系统的源文件。这样就算是换啦电脑，重新下载源文件后，重新安装hexo环境，就可以重新发布博客啦。

