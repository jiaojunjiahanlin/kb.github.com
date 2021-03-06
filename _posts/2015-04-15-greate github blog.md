---
layout: post
title: github 如何自己搭建blog博客
---
# Qiniu 怎样在github上面搭建自己的博客详细解决方案。

[![Build Status](https://api.travis-ci.org/qiniu/c-sdk.png?branch=master)](https://travis-ci.org/qiniu/c-sdk)

[![Qiniu Logo](http://qiniutek.com/images/logo-2.png)](http://qiniu.com/)



## 问题解决方案

- 第一点：我们要在github上面自己注册一个账号，然后新建一仓库。并且在setting中设置automatic page generate。一步一步的按照提示设置生成。

----------

- 第二点：在你的本地装git工具。因为下面我们要用到git工具来完成文件发布到远程的仓库。

----------
- 第三点：在git的cmd中执行：git clone https：//你的远程库的url。功能是在本地生成一个备份。

----------
- 第四点：到http://jekyllthemes.org/可以下载到jekyll很多大神的模板博客网站。可以之间clone到本地，然后全部拷贝到刚才第三步clone的文件夹中。

----------
- 第五步：修改刚才文件夹中的-config.yml文件中的baseurl： /你的远程仓库的名字。记住了baseurl后面有个空格。

----------
- 第六步：
- `$ git add .`
- `　$ git commit -m "first post"`
- `git push origin gh-pages`

----------
然后就可以到远程仓库去查看你的博客了：地址在setting中的automatic page generate上面可以看到url地址。
　

## 结果演示

http://jiaojunjiahanlin.github.io/kb.github.com/

## 许可证

Copyright (c) 2012 http://jiaojunjiahanlin.github.io/kb.github.com/
