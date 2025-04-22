## revit-mcp

[English](README.md) | 简体中文

revit-mcp 是一个基于 Revit 软件的 mcp 协议实现框架。允许通过兼容mcp协议的AI对话客户端驱动Revit。

### 例子

[ColorSplash](https://www.youtube.com/watch?v=mUJGSjQHBm8)

### 项目组成

项目主要分为以下三部分：

[**revit-mcp仓库**](https://github.com/revit-mcp/revit-mcp)：与对话AI对话客户端连接部分。负责向ai对话客户端提供可执行功能和与revit通讯。

[**revit-mcp-plugin仓库**](https://github.com/revit-mcp/revit-mcp-plugin)：这是一个revit插件，用于接收ai的命令、装载命令集、执行具体功能。

[**revit-mcp-commandset仓库**](https://github.com/revit-mcp/revit-mcp-commandset)：功能集是实际可执行的具体命令，基于revit外部事件进行包装。开发者可以通过在命令集中增加功能，或者定制个人的工作集。

### 安装与使用

你可以在这里查看如何安装和使用项目：[Driving Revit through MCP](https://github.com/revit-mcp/revit-mcp-plugin/wiki/Driving-Revit-through-MCP)

### 加入我们

你可以通过[Discord](https://discord.gg/EYZFN9Xb4J)或者[QQ群](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=kLnQiFVtYBytHm7R58KFoocd3mzU_9DR&authKey=fyXDOBmXP7FMkXAWjddWZumblxKJH7ZycYyLp40At3t9%2FOfSZyVO7zyYgIROgSHF&noverify=0&group_code=792379482)联系我们，期待与你共同建设项目。

**祝你玩得愉快！**
