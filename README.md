# 业务网关

[![diablo-logo.png](https://i.postimg.cc/d32BfxD4/diablo-logo.png)](https://postimg.cc/YLSYG86W)

# 业务网关系列文章

## 背景

1、[网关的背景](docs/网关的背景.md)

## 设计

1、[用到的技术栈](docs/技术栈.md)

2、[服务网关功能](docs/网关功能.md)

3、[组件介绍](docs/组件介绍.md)

4、[网关请求时序](docs/网关请求时序.md)

5、[缓存方案](docs/缓存方案.md)

6、[后台用例介绍](docs/后台用例介绍.md)

7、响应式

## 实现

### 插件

+ [分流插件](docs/分流插件.md)

+ [协议转换插件](docs/协议转换插件.md)

+ 黑白名单插件

+ [限流插件](docs/限流插件.md)

+ [鉴权插件](docs/鉴权插件.md)

+ 签名插件

### 后台管理

### 高可用

+ [探活机制](docs/服务探活.md)
+ [故障快速转移](docs/故障快速转移.md)

### 性能

## 线上运维

+ [预发环境](docs/预发环境.md)

+ 主机同步

+ [AccessLog](docs/AccessLog.md)

## 遇到过的问题

+ 日志量过大导致load值尖峰

+ [服务部署时出现异常日志](docs/优雅下线.md)

## demo运行

> 简要介绍如何将项目跑起来

 + [操作手册](docs/操作手册.md)

## 来自于开源

> 项目借鉴了[soul网关开源项目](https://github.com/Dromara/soul)，其中后台部分拿过来扩展一些功能，网关项目借鉴了思路以及大部分核心代码重新进行了针对性的整合

