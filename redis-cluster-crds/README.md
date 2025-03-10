# Redis Cluster Operator

## Operator功能说明

1.Redis Cluster Operator用于在kubernetes集群部署Redis集群

2.提供对Redis集群的部署管理

3.仅配置存储类和持久化存储尺寸即可部署。 持久化存储用于存储各个Redis的节点信息。

4.提供对Redis集群的备份及恢复

5.每个Operator全局部署一次即可

6.有Redis相关自定义资源在运行时，请勿删除Operator

7.通过HELM删除Operator，将导致Redis集群完全不可用

8.Redis使用详情请参阅Redis官方文档

