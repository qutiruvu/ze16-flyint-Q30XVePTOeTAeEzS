## 思维导航

* [前言](#_label0)
* [Anno.Core 项目介绍](#_label1)
* [Viper 项目介绍](#_label2)
* [项目功能](#_label3)
* [整体架构](#_label4)
* [相关 NuGet 库](#_label5)
* [项目演示效果](#_label6)
* [项目源码地址](#_label7)
* [优秀项目和框架精选](#_label8):[veee加速器](https://blog.liuyunzhuge.com)

## 前言

今天大姚给大家分享一个基于 .NET 开源、功能强大的分布式微服务开发框架：Anno.Core。

![image](https://img2024.cnblogs.com/blog/1336199/202510/1336199-20251023223823375-1821882917.png)

## Anno.Core 项目介绍

Anno.Core 是一个基于 .NET 开源、功能强大的分布式微服务开发框架，致力于简化分布式、微服务系统的构建。框架原生支持 gRPC 和 Thrift 两种高性能 RPC 通信协议，自带服务发现、调用链追踪、Cron 调度、限流、事件总线、CQRS 、DDD、插件化开发等。

![image](https://img2024.cnblogs.com/blog/1336199/202510/1336199-20251023223834626-489901304.png)

## Viper 项目介绍

Viper 是一个基于 Anno.Core 微服务引擎开发的 Dashboard 项目、示例项目。

![image](https://img2024.cnblogs.com/blog/1336199/202510/1336199-20251023223845679-244401324.png)

## 项目功能

Anno.Core 包含服务注册中心、服务发现、健康检查、负载均衡、限流、失败重试、链路追踪、资源监控等功能。

* **服务注册与发现**：自动管理服务生命周期，支持动态扩缩容；
* **分布式调用链追踪**：无缝集成链路监控，助力问题定位与性能分析；
* **多策略限流控制**：基于令牌桶/漏桶算法，保障系统稳定性；
* **事件总线（Event Bus）**：实现松耦合的领域事件驱动架构；
* **CQRS 与 DDD 支持**：提供清晰的读写分离模型与领域驱动设计实践路径；
* **插件化架构**：通过模块化设计实现功能按需加载，提升系统可维护性与扩展性。

## 整体架构

![image](https://img2024.cnblogs.com/blog/1336199/202510/1336199-20251023223905570-247931859.png)

## 相关 NuGet 库

![image](https://img2024.cnblogs.com/blog/1336199/202510/1336199-20251023223921124-992911128.png)

## 项目演示效果

![image](https://img2024.cnblogs.com/blog/1336199/202510/1336199-20251023223823375-1821882917.png)

![image](https://img2024.cnblogs.com/blog/1336199/202510/1336199-20251023223936307-289944227.png)

![image](https://img2024.cnblogs.com/blog/1336199/202510/1336199-20251023223942195-716530992.png)

![image](https://img2024.cnblogs.com/blog/1336199/202510/1336199-20251023223947250-941921197.png)

![image](https://img2024.cnblogs.com/blog/1336199/202510/1336199-20251023223952690-344472832.png)

![image](https://img2024.cnblogs.com/blog/1336199/202510/1336199-20251023223958327-129109103.png)

![image](https://img2024.cnblogs.com/blog/1336199/202510/1336199-20251023224004196-1068930051.png)

![image](https://img2024.cnblogs.com/blog/1336199/202510/1336199-20251023224010514-140680952.png)

![image](https://img2024.cnblogs.com/blog/1336199/202510/1336199-20251023224017482-649474835.png)

## 项目源码地址

更多项目实用功能和特性欢迎前往项目开源地址查看👀，别忘了给项目一个Star支持💖。

* **Viper 开源地址：**https://github.com/duyanming/Viper
* **Anno.Core 开源地址：**https://github.com/duyanming/Anno.Core

## 优秀项目和框架精选

该项目已收录到C#/.NET/.NET Core优秀项目和框架精选中，关注优秀项目和框架精选能让你及时了解C#、.NET和.NET Core领域的最新动态和最佳实践，提高开发工作效率和质量。坑已挖，欢迎大家踊跃提交PR推荐或自荐（**让优秀的项目和框架不被埋没🤞**）。

* **GitHub开源地址：**https://github.com/YSGStudyHards/DotNetGuide/blob/main/docs/DotNet/DotNetProjectPicks.md
* **Gitee开源地址：**https://gitee.com/ysgdaydayup/DotNetGuide/blob/main/docs/DotNet/DotNetProjectPicks.md
