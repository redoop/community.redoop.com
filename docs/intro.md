---
sidebar_position: 1
---

# 介绍

​Redoop Community 是一款基于 Apache Ambari + Apache Hadoop 生态的大数据基础软件产品，旨在为用户提供更加方便和高效的大数据集群管理方案。

作为 Apache Ambari 的补充和扩展，Redoop Community 主要为大家提供 Apache 社区未发版的较稳定 Snapshot 版本，以及已发版的 Release 包的镜像站。

​Redoop Community 主要有下列几个优势：兼容上游、方便部署以及多云支持。

## 兼容上游

​Redoop Community 不对 Apache Ambari 的源代码进行深度修改，保证了与 Apache Ambari 的代码完全兼容 Apache Hadoop 生态发布的原生软件。并且我们保留了 Apache Ambari 的其他兼容性特点，例如对不同的操作系统的支持、对不同的硬件平台的支持、对不同的软件生态系统的支持等。这些兼容性特点使得 Redoop Community 可以在更广泛的环境中使用，为用户带来更大的便利。

​我们也会定期发布新版本，并在新版本中新增 Apache Ambari 的最新版本的支持，同时也保留对旧版本的支持。这样，用户就可以在 Redoop Community 中轻松地进行版本升级。

## 方便部署

​Redoop Community 团队会统一编译并提供 Ambari RPM 包，保证版本的一致性。用户可以在 Redoop Community 的镜像站上下载这些 RPM 包，然后直接使用 yum 进行安装。这样就可以省去自己从源码编译的步骤，并直接使用这些软件包快速搭建自己的大数据集群，简化部署流程。

​我们也将在未来支持一键部署到云平台的功能，用户可以几分钟内在云平台上搭建自己的大数据集群，只需提供云平台的账号信和一些基本的配置参数即可，Redoop Community 就可以自动完成部署流程，该方式极大地简化了部署复杂度，使用户可以快速体验 Apache Ambari。

## 多云支持

最后我们再来看看 Redoop Community 即将到来的多云支持：

​我们会支持包括在 AWS、Azure、GCP、Alibaba Cloud、QingCloud、Ucloud  等一个或多个云平台上使用，并且能够互相迁移，这样就可以根据自己的需要随时调整集群的部署位置，而更好地利用云平台的资源，获得更大的灵活性与可扩展性。

​并且用户可以根据实际的负载情况，通过 Redoop Community 自动调整虚拟机的个数，来动态扩/缩容集群，从而达到节省成本的目的。此外，Redoop Community 还可以根据用户的应用场景，提供合适的资源配置方案，帮助用户更好地利用资源。