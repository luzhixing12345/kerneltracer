# kerneltracer

kerneltracer是一个内核驱动程序,用于linux的内存,网络和驱动调试

此驱动应当在 v4.x, v5.x, v6.x 的linux kernel中运行良好, 后续考虑兼容早期版本与未来的版本

文档分为4个部分,分别介绍编译,调试,kerneltracer的使用及其开发文档. 如果您已对linux较为熟悉可以直接跳至第三部分usage

- 如何编译linux: build
- 如何调试linux: debug
- 如何使用kerneltracer: usage
- 开发文档: develop

## 前言

此文档撰写之初笔者只有一个大致的想法, 这个项目大概会持续的推进很长很长一段时间, 直到这个工具真正的可用

我们假定读者具备一定的linux使用经验, 文档的内容尽量清晰,详尽. 工具的使用应尽量便捷,直观

总之, have a try ~