# thinkcmf5 阿里云OSS存储插件

#### 介绍
参考七牛云存储插件 实现的thinkcmf5的阿里云OSS存储插件,实现了最基础的同步上传到阿里云oss功能

#### 安装教程

1. 开通阿里云OSS存储服务 https://www.aliyun.com/product/oss

2. 项目安装oss存储SDK包  https://help.aliyun.com/document_detail/85580.html

3. 下载本插件包,oss文件夹放在项目public/plugins目录下

4. 项目管理后台 - 插件中心 - 插件列表 安装OSS上传插件,安装完毕后进行相应设置

5. 项目管理后台 - 设置 - 文件存储 存储类型选择为阿里云OSS

6. 安装完毕,上传附件的同时也会上传到阿里云OSS外部存储

7. 前台使用`cmf_get_image_url()`函数获取图片，可自动获取云存储图片路径




#### 使用composer安装oss存储SDK

1. 执行`composer require "aliyuncs/oss-sdk-php:~2.4"`

2.安装完毕
