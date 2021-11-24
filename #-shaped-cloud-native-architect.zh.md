[TOC]

# '#'-Shaped Cloud-Native Architect

## 背景

### 背景：什么是架构师

Ref: [Types of Software Architects](https://medium.com/@nvashanin/types-of-software-architects-aa03e359d192)

根据职责范围、技术类型、行业特质可以将Architect分为2种：

- Software Architect： make high-level design choices based on their programming experience.

![type of architect](./imgs/wiki-type-of-architect.png)

> 应用级、解决方案级、企业级没有高低之分，区别在于所负责的软件模块、抽象程度不同；same as 二进制、汇编、Java、Http，编写、抽象、编排，逐层构建我们想要的产品

- Domain Architect

![img](https://miro.medium.com/max/700/1*6ZOJNn4SDSD9KYlFHr34_A.png)

> 从事某一个专业领域的架构，可以是技术领域、也可以是业务领域。运用经验，用某一个领域的技术构建适用的软件、构建某一个领域适用的软件。

而想要成为一名合格的架构师，除了具备过硬的技术能力外，还需要有一定的架构经验和领域知识：

- Level of the Architect

![img](https://miro.medium.com/max/700/1*n1Zqvw8Bk-_o8RWXnzS5KQ.png)

> Domain+，Platform+，多领域知识、触类旁通

## 背景：什么是云原生

![](/Users/adliao/Documents/Y3JlZGVudGlhbC1zaGFyZWQ-/documents/cloud-native-spaces/imgs/cloud-native-icon.png)

- 微服务
- DevOps
- CI
- 容器化

## What 我认为的云原生架构师
### 云原生架构师
“软件”代指很多东西，“软件设计”也不只是指一个进程、一个服务、一个系统的设计。在不同的层级（操作系统、应用软件、互联网）和不同的领域（移动端、服务端、云端）很多技术原理是高度一致的，当你的技能树广度和深度俱佳时，你能很快的拓展到其他领域。很多厉害的科学家同时也是哲学家，不同领域的知识能够帮助他从不同角度看问题。

在云原生时代，软件的抽象层级也随之变化（云、多机、弹性 <- 单机、多线程、稳定）；大量新的技术涌现，单个开发者的工作产出明显高于过去，10x Developer；疫情下全球一体化进程加速发生（很多Remote工作），技多不压身...


我所理解的云原生时代的架构师，应该具备不止于“T”or“π”的能力：多领域的交叉、多平台的混合是大趋势（端到端应用、多云、系统集成），在打造专精技能的同时，还需要考虑横向拓展。


### '#'的含义

因此，我期望的一个技能模型是“#”状的：

- 多精多强，广度兼优

- （像消消乐一样）遇到一个新技能/领域时，能借助其他已有技能来学习

- 多个技能叠加buff，战斗力翻倍

- 通过拓展边界，你的定位（网心）也会不断变化，不要给自己设限

## Why 为什么云原生架构师需要#的能力

### 为什么要成为云原生架构师

#### 软件技术进步的方向：抽象、封装、多态

云计算则是站在所有硬件软件之上，提供最高层级的封装和解决方案。

云时代以前，大家面相对象，面相数据库，面相Java，面相前端；云时代之后，只有一种编程模式-面相云编程-cloud native。

### 为什么需要“#”的能力

#### 相似的理论知识

事件驱动
缓存
一致性协议

1. 封装为上层技术的发展提供便利
2. 大多数计算机技术问题早在OS阶段就已经有解决方案
   
#### 第一性原理

万物既有定数

#### 快速的拓展

## How 如何云原生

### 架构设计 Architecture

### 开发部署 DevOps

### （闲谈）项目管理 Project Management

## 脑洞：未来的开发模式

Low-Code

Value Driven desgin - no development

BA with AI-Developer

Architecture as a Service(AaaS)

- [serverless framework](https://github.com/serverless/serverless)


这些脑洞其实并不是空想，google一下你会发现相关的讨论从几年前就开始了。而随着云计算的成熟，软件服务变成了“即插即用的设备”，并且还可以进行租赁、试用。

就像汽车变速箱一样，你的档位越高，能驱动的力就越大，车就跑的越快。齿轮传动（杠杆原理），小齿轮转速不变的情况下，大齿轮越大扭矩越大。

> 36公斤的力量怎么推动一公吨的车重呢？而且动辄数千转的引擎转速更不可能恰好成为轮胎转速，否则车子不就飞起来了？幸好聪明的人类发明了「齿轮」，利用不同大小的齿轮相连搭配，可以将旋转的速度降低，同时将扭矩放大。由于齿轮的圆周比就是半径比，因此从小齿轮传递动力至大齿轮时，转动的速度降低的比率以及扭矩放大的倍数，都恰好等于两齿轮的齿数比例，这个比例就是所谓的「齿轮比」。

![img](https://cdn.hswstatic.com/gif/dual-clutch-transmission-13.gif)


云原生开发者就是变速箱，他能够灵活的选用档位，驱动不同级别的业务需求。

## 资料

- [什么是架构师？](https://zhuanlan.zhihu.com/p/38780884)
- [Cloud-Native Architecture: What It Is and Why It Matters](https://www.contino.io/insights/what-is-cloud-native-architecture-and-why-is-it-so-important)
- [什么是云原生？这回终于有人讲明白了](https://juejin.im/post/6844904197859590151)
- [Types of Software Architects](https://medium.com/@nvashanin/types-of-software-architects-aa03e359d192)
- [团队协作的秘诀：为什么小团队效率更高](http://www.woshipm.com/it/94517.html)
- [serverless framework](https://github.com/serverless/serverless)
- [什么是扭矩](https://sites.google.com/site/shejishe4/Home/什么是扭矩)
