# .NET Demo

## WebSocket

包含HTML文档，演示HTML WebSocket客户端与.NET后台通讯

## KeyboardRecord


- 简介

	Win系统带有API可以获取键入值，本小程序主要应用了一个网上广为流传的类，可以说一个测试DEMO。有俗称为键盘钩子

- 编程思路

	使用Win API获取建入值

- 相关技术

	Win API

- 功能

	开启记录，记录每个键盘键入值，最终可以导出

## SocketDemo


- Socket简介


	通过TCP/IP与仪器或设备通讯，在C#语言中，我们通常采用Socket。本项目是一个简单的Socket建立服务监听与Socket作为客户端请求的一个示例。

- 项目结构

	- 客户端项目 SocketClient

		主要负责作为Socket客户端发起连接请求，并发送数据

	- 服务端项目 SocketDemo

		主要负责作为Socket服务端，监听端口并接收连接请求，并返回应答数据

- 项目演示

	- 先运行SocketDemo进行服务监听
	- 运行SocketClient进行模拟连接，并发送接收数据。

## Draw


- 应用场景

	设置名单，进行抽签

- 编程思路

	使用Timer定时器，运行定时器进行名单随机滚动，停止定时器获得抽签结果

- 相关技术

	- 随机数
	- Excel读取/导出
	- XML文档读写

- 相关类库

	- C1.C1Excel Excel操作相关

- DEMO 功能

	- 读取Excel名单
	- 名单随机抽签
	- 评分功能
	- Excel导出功能

## QRCode


- QR二维码

	二维码的一种

- 相关类库

	ThoughtWorks.QRCode 第三方类库

- DEMO功能

	- Encode 生成二维码图片

		- Encoding 编码
		- Correction Level 等级
		- Version 版本
		- Size 大小

	- Decode 解密二维码
	