# 基于云开发的弹幕小程序


# 云开发 quickstart

这是云开发的快速启动指引，其中演示了如何上手使用云开发的三大基础能力：

- 数据库：一个既可在小程序前端操作，也能在云函数中读写的 JSON 文档型数据库
- 文件存储：在小程序前端直接上传/下载云端文件，在云开发控制台可视化管理
- 云函数：在云端运行的代码，微信私有协议天然鉴权，开发者只需编写业务逻辑代码

## 参考文档

- [云开发文档](https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html)



## 录屏
因为小程序有上传图片功能，所以属于社交笔记范畴，个人主体小程序未开放，所以，不能直接扫描小程序码直接看。放一下录屏（如下）：


![录屏](screen-gif.gif)

## 更新日志


- v1.0.3（当前版本）
  - 2019-09-06
  - improvements
    - 新增无序弹幕功能，可在右下角切换有序与无序；
    - 新增相册页；
    - 新增添加相册页；
  - bug_fixes
    - '限制上传空图片列表；
  
- v1.0.2
  - 2019-09-05
  - improvements
    - 新增Tabbar；
    - 新增弹幕详情列表页，点击弹幕可见；
    - 新增授权页，发送弹幕前用户需先授权用户信息
  - bug_fixes
    - 修复可发射空弹幕的漏洞；
  
- v1.0.1
  - 2019-09-04
  - improvements
    - 新增弹幕背景图,下拉可切换背景；
    - 优化添加弹幕页样式；
  - bug_fixes
    - 修复背景图片在不同大小屏幕设备下的拉伸问题（但图片资源长度有限，iPhoneX等长屏设备会出现空白，其他设备正常，待以后替换图片资源）；

- v1.0.0
  - 2019-09-03
  - improvements
    - 项目搭建
  - bug_fixes
    - 无
