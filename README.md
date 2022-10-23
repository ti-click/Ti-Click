# Ti-Click

**Ti-Click**是一个基于浏览器的编程环境。开发人员无论是在平板还是电脑上打开浏览器，选择他想尝试的Template，就可以在云端为他提供一个App Template的编程环境。

如何跑起一个TiDB cluster，试试TiDB SQL等。这些内容无论是文字，视频还是互动性教学，更多的是以TiDB数据库能力为核心。我们希望从软件开发者的角度来看待，如何使用TiDB和基于TiDB开发程序。在有了这个直观的互动基础上，我们就可以再推广，使用TiDB的好处。

## [TiDB Quick Start](https://glistening-pudding-ecfa72.netlify.app/) ⟵由此进入TiDB App Template
![image](https://user-images.githubusercontent.com/81517726/197374865-0518c9b8-134c-4d3f-8667-c03b3996e8b8.png)

## Ti-Click 解决的问题

1. 方便快速的开启TiDB开发之旅: 开发人员提供一个基于浏览器的编程环境，开发人员无论是在平板还是电脑上打开浏览器，选择他想尝试的Template，就可以在云端为他提供一个App Template的编程环境。在我们右边的操作台，依次点击导入数据，编译，部署，打开前端页面的按钮，就可以访问一个非常完整，并且带有页面的项目当然同时也会在云端提供相应的TiDB环境，比如说TiDB Sandbox或者是TiDB Cloud。

<iframe src="//player.bilibili.com/player.html?aid=935575055&bvid=BV1mT4y1m7J5&cid=479613888&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" style="width: 640px; height: 430px; max-width: 100%"> </iframe>

2. 展现了TiDB对多种语言和框架支持的生态多样性: 我们目前已经支持了包含Python，Java，Nodejs，Golang，PHP,SpingMVC, Django,Laravl多种语言与框架。这里我们列出的图标，都是基于TiDB 或者 TiDB Cloud的可以正常运作的App Template。这些项目包含了非常完整的前端，后端，以及数据相关的处理代码。

<iframe src="//player.bilibili.com/player.html?aid=935522787&bvid=BV1pT4y1m71r&cid=479612943&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" style="width: 640px; height: 430px; max-width: 100%"> </iframe>

## Ti-Click 与 Ti-Click++

Hackathon 2021 上我们推出了基于Eclipse Che的IDE开发环境，并且为了体现展现了TiDB对多种语言和框架支持的生态多样性，我们支持了包含Python，Java，Nodejs，Golang，PHP,SpingMVC, Django,Laravl多种语言与框架的Sample App。

#### 但原先的Ti-Click存在三个非常大的问题:

1. Eclipse Che的维护

Eclipse Che需要自己维护Eclipse Che。Eclipse Che基于Kubernetes提供了Operator的部署方案，虽然部署方案较为成熟，但是如果对Kubernetes的熟练程度不高或者苦于Kubernetes的排错，那么使用Eclipse Che绝对是一个灾难。

2. 耗费资源量巨大

Online IDE因为包含了编程环境，部署环境以及演示环境，所以他所需的资源是惊人的。往往一两位用户的使用，就需要动辄每月几十美金的资源。

3. Sample App无法专注于技术本身

尽管Ti-Click提供了繁多的语言与框架的Sample App，但是这些语言和框架也存在着业务不统一的问题。比如说Java的Sample App是宠物医院，但是Python的Sample App却是图书商城。那么对用户来说，不同的Sample App需要理解不同的业务是非常痛苦的。

#### Ti-Click++

为解决这些问题，**Ti-Click++** 使用gitpod的云服务，一次性解决Eclipse Che运维难和资源消耗问题。此外我们将统一业务模型，使用Real World的模板进行改造。这样可以让用户只需要理解一种业务，但是可以同时理解多种语言链接和使用TiDB的方案。

## 现存问题

TiDB是一款有infra属性的产品，所以对开发人员来说，缺乏直观的使用感受。尤其是在对用户进行宣传的时候，会有一些困难。目前面对开发者，我们包括友商提供的仅仅是文档。在github上提供一些Template。但是，要知道，一名开发者在部署一个Template的时候，他要配置环境，下载依赖，进行编译。这些行为麻烦不说，还有可能对他的本地环境产生影响。

## Road Map

1. 与TiDB Cloud打通

最优先的计划是想和TiDB Cloud打通，让想尝试Ti-Click的小伙伴优先选择TiDB Cloud。

3. 更多的厂商

我们还想吸引更多的厂商来丰富我们的生态，比如说一些SaaS的厂商，吸引他们来提供基于TiDB的代码案例，放到我们的Ti-Click平台。目前日本的一家游戏厂商其实就自研了一款链接TiDB的PHP的组件，我们目前也在把这个组件的Template放到Ti-Click中来。

**开源社区万岁**
