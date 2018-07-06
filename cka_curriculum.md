CKA考试大纲

准备在2018.8月份考试，先整理一下官方考点

想看官网的考点的请戳[这里](https://github.com/wulalaya2py/curriculum/blob/master/certified_kubernetes_administrator_exam_v1.9.0.pdf)
# 5% - 容器调度
* 使用label Selectors调度Pod
* 理解DaemonSets的角色
* 理解资源限制怎样影响Pod调度
* 理解如何跑多个调度器并且如何调整调度器去影像Pod
* 手动调度一个Pod
* 展示 Scheduler的事件
* 知道如何配置k8s的调度器

# 5% - 日志/监控
* 理解如何监控所有的集群组件
* 理解如何监控应用
* 管理集群组件的日志
* 管理应用的日志

# 8% - 应用生命周期管理
* 理解Deployments并知道如何使用滚动升级和回滚
* 知道多种方法去配置应用
* 知道如何扩容/缩容 应用
* 知道创建一个自愈的应用的重要性

# 11% - 集群维护
* 理解k8s集群的升级步骤
* 保证操作系统的升级
* 实现备份和还原的方案

# 12% - 安全
* 知道如何设置鉴权和授
权
* 理解k8s的安全原语
* 知道如何配置网络策略
* 为集群组件创建和管理TLS证书
* 安全使用镜像
* 定义安全的上下文
* 安全密钥的固化存储
* 学会使用RBAC

# 7% - 存储
* 理解永久存储，知道如何创建
* 理解 volume的 access mode
* 理解 persistent volume 的声明原语
* 理解 k8s的 storage obeject
* 知道如何为应用设置persistent storage

# 10% - 解决问题
* 解决应用失败问题
* 解决控制面板挂了
* 解决work node 挂了
* 解决网络问题

# 19% - 核心概念
* 理解k8s的api设计
* 理解k8s的集群架构
* 理解service 和其他的
network设计

# 11% - 网络
* 理解集群节点的网络配置
* 理解Pod的网络概念
* 理解service的网络
* 部署且配置network的负载均衡
* 知道如何使用ingress rule
* 知道如何配置和使用集群dns
* 理解CNI

# 12% - 安装，部署 和验证
* 设计k8s集群
* 安装k8s master和节点，包括使用 TLS bootstrapping
* 配置安全的集群沟通
* 配置高可用的k8s集群
* 知道哪里去获取k8s的release  binary
* 规划底层去部署k8s集群
* 选择网络方案
* 选择k8s的infrastructure的配置
* 在集群内跑e2e测试
* 分析e2e测试结果
* 跑n2n的测试
