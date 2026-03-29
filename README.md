# spring-boot-starter-parent

> Spring Boot 3.x 企业级开发父 POM，统一管理常用依赖版本

## 简介

基于 Spring Boot 3.5.13 的父 POM 项目，预配置了企业级开发中常用的依赖版本，简化项目搭建过程。

## 特性

- 基于 Spring Boot 3.5.13 + Java 21
- 统一管理常用依赖版本
- 开箱即用的企业级技术栈

## 技术栈

| 技术 | 版本 | 说明 |
|------|------|------|
| Spring Boot | 3.5.13 | 基础框架 |
| Java | 21 | JDK 版本 |
| Mybatis-Flex | 1.11.6 | ORM 框架 |
| Redisson | 4.3.0 | Redis 客户端 |
| Sa-Token | 1.45.0 | 权限认证 |
| FastJson2 | 2.0.53 | JSON 处理 |
| Druid | 1.2.25 | 数据库连接池 |
| Hutool | 5.8.38 | 工具类库 |
| EasyExcel | 4.0.3 | Excel 处理 |
| POI-TL | 1.12.2 | Word 模板引擎 |
| TTL | 2.14.5 | 线程上下文传递 |
| P6Spy | 1.12.1 | SQL 日志 |

## 使用方式

在项目的 `pom.xml` 中继承此父 POM：

```xml
<parent>
    <groupId>me.liliudong</groupId>
    <artifactId>spring-boot-starter-parent</artifactId>
    <version>3.5.13.01</version>
</parent>
```

然后直接引入依赖，无需指定版本：

```xml
<dependencies>
    <dependency>
        <groupId>com.mybatis-flex</groupId>
        <artifactId>mybatis-flex-spring-boot-starter</artifactId>
    </dependency>

    <dependency>
        <groupId>org.redisson</groupId>
        <artifactId>redisson-spring-boot-starter</artifactId>
    </dependency>

    <dependency>
        <groupId>cn.dev33</groupId>
        <artifactId>sa-token-spring-boot3-starter</artifactId>
    </dependency>
</dependencies>
```

## 许可证

[Apache License 2.0](LICENSE)

## 作者

李刘东 - [GitHub](https://github.com/mofishless) - [Blog](https://liliudong.me)
