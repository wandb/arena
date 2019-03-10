﻿# 路线图

本文档给出了 Arena 开发的路线图。


### 2018

#### 功能特点

- 增强了训练作业
  - 转为采用 MPI Operator
  - 根据不同的训练类型设置默认 CPU/内存限制：tf Operator、MPI Operator
  -支持群调度器
  - Pytorch Operator

- 训练历史记录管理
  - 使用 CRD 管理训练历史记录

- 集成数据
  
- 多租户

- 易于安装


#### 稳定性/可靠性

- 端到端测试
- 单元测试
- 自动生成 arena docker镜像
