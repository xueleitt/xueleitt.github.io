---
layout:     post
title:      Mac 无法连接Android手机
date:       2016-03-14 12:31:19
categories: tools
---

1. 终端输入 system_profiler SPUSBDataType,查看usb连接信息,
如果查不到,说明是手机设置问题,继续检查手机
    ~/system_profiler SPUSBDataType

2. 把Vendor ID 添加到 adb_usb.ini文件中
    vi ~/.android/adb_usb.ini