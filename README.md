# meepo
基于jta，仿GTS实现的分布式事务框架

meepo是一个类XA/2PC（1pc+1）机制的分布式事务管理器。实现了Spring JTA接口，集成dubbo，提供阿里GTS的核心功能。

meepo基于jta实现 https://github.com/liuyangming/jta

meepo = jta的基础代码+GTS的原理流程

使用样例：https://github.com/wxbty/meepo-test

架构介绍+源码跟踪：https://wxbty.github.io/2018/08/01/start/one/ （持续更新中..）

若您有任何建议，联系本人wxb_101@163.com
