# M5-StickV/UnitV
===

## 关于 StickV/UnitV

M5Stick-V是一款搭载Kendryte K210的AIOT（AI + IOT）摄像头,集成双核64位RISC-V CPU和最先进的神经网络处理器边缘计算片上系统（SoC）

M5stickV AI 摄像头具备机器视觉能力,配备OmniVision OV7740图像传感器,采用OmniPixel®3-HS技术,提供相比同类最佳的低光灵敏度,支持多种视觉识别能力的它（ 如实时获取被检测目标的大小与坐标 • 实时获取被检测目标的种类）,并且能够在低功耗情况下进行卷积神经网络计算,因此M5StickV会是一个很好的零门槛机器视觉嵌入式解决方案,支持MicroPython开发环境,这使得你在使用M5stick-V上进行项目开发时,程序代码将会更加精简.

UNIT-V是一款搭载Kendryte K210的AI视觉处理摄像头单元,集成双核64位RISC-V CPU和最先进的神经网络处理器边缘计算片上系统.UNIT-V AI摄像头体积非常小巧,适合嵌入到各种设备当中,具备机器视觉处理能力,支持多种图像识别能力（ 如实时获取被检测目标的大小与坐标 • 实时获取被检测目标的种类）,并且能够在低功耗情况下进行卷积神经网络计算,因此UNIT-V会是一个很好的零门槛机器视觉嵌入式解决方案.它支持MicroPython开发环境,这使得你在使用UNIT-V上进行项目开发时,程序代码将会更加精简.搭载OV2640/OV7740 200万像素图像传感器,是机器视觉项目的理想选择.机身配备两个可编程按键,正面有一颗RGB LED指示灯,方便进行状态显示.底部提供一个兼容HY2.0*4P接口和一个TYPE-C接口,可以与主控设备进行连接.支持TF卡扩展内存,相关素材及模型文件调用使用更方便.

English(./README.md) | [中文](./README-zh_CN.md)

<img src="https://static-cdn.m5stack.com/resource/docs/products/core/m5stickv/m5stickv_01.webp" alt="m5stickv" width="200" height="200"><img src="https://static-cdn.m5stack.com/resource/docs/products/unit/unitv/unitv_01.webp" alt="unitv" width="200" height="200"><img src="https://static-cdn.m5stack.com/resource/docs/products/unit/unitv_ov7740/unitv_ov7740_01.webp" alt="unitv_ov7740" width="200" height="200">


运行在 M5-StickV/UnitV 上的脚本，玩得开心～

## 目录结构

| 目录 | 描述 |
| --------- | ----------- |
| application | 一些复杂的应用 |
| basic | 基本的 micropython 使用 |
| board | 运行 Python 代码，配置你的 sipeed 硬件 |
| hardware | 硬件 API 使用例程 |
| m5stack | 与 M5Stack 其他产品联动 |
| machine_vision | 视觉处理相关,包括机器视觉以及AI处理 |
| modules   | 外部外设模块使用, 比如 Grove 模块, sp-mod 模块 |
| multimedia | 普通的多媒体功能,比如音频、视频、GUI、游戏等 |
| network | 网络相关例程 |
