# autoMsg

![GitHub Stars](https://img.shields.io/github/stars/joe-qai/autoMsg)
![GitHub Forks](https://img.shields.io/github/forks/joe-qai/autoMsg)
![Java Version](https://img.shields.io/badge/java-8+-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## 项目简介

`autoMsg` 是一个基于 Java 的 QQ 自动消息发送工具，支持定时发送消息、消息模板、批量发送等功能。

## 核心功能

- 📧 **自动发送**: 定时自动发送消息
- 📋 **消息模板**: 支持消息模板管理
- 📤 **批量发送**: 支持批量发送消息
- ⏰ **定时任务**: 支持定时发送任务

## 技术栈

- **Java**: 8+
- **依赖**: QQ API 相关库

## 快速开始

```bash
# 编译项目
mvn clean compile

# 打包运行
mvn package
java -jar target/autoMsg.jar
```

## 项目结构

```
autoMsg/
├── src/main/java/
│   └── com/example/
│       ├── Main.java          # 主入口
│       ├── QQClient.java      # QQ 客户端
│       └── Scheduler.java     # 定时任务
├── pom.xml                    # Maven 配置
└── README.md
```

## 使用说明

1. 配置 QQ 账号信息
2. 设置消息内容和发送时间
3. 运行程序自动发送消息

## 注意事项

- 请遵守 QQ 使用协议
- 不要滥用自动发送功能

## 许可证

MIT License
