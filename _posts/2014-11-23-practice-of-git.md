---
layout: page
title: git 常用操作
---

##git 常用操作##

####1.多次提交合并####

git rebase -i

####2.查看提交到本地没有PUSH到远端的提交####
git log <本地分支> --not --remotes=<远端分支>

example:git log gh-pages --not --remotes=*/gh-pages

***
更新中





