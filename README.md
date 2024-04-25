# 信息

**作品名称**：基于Apache的城乡车流量模型的设计与开发

**作者姓名**：李世阁

**创作时间**：阳历2024年3月25日，即农历甲辰龙年二月二十六日

**担任职责**：负责产品整体框架搭建、登录认证、国际化翻译模块以及修改操作

**作品性质**：本设计对城乡车流量进行回顾、在线与展望，结合快速排序、希尔排序、冒泡排序、选择排序四大算法，既要展示Java或Python等代码实例，又要对算法进行可视化呈现，对交通大数据进行分析。交通是城市发展的主要动力，无论是生产要素的流动，还是对于对于城乡体系的发展，都具有十分重要的作用；此设计可以帮助我们重温基础知识，为城乡车流量的发展贡献绵薄之力。

**主要内容**：主要内容分为信息、摘要、目录、引言、报告、结论、文献、附录、致谢九大模块，引言下面有背景和简介两个分支，报告下面有概述、计划、流程、思考、概论、思想、对比、分析、问题、要点、测试、环境、评价、结果、结论、其它、建议十八个分支。从需求方面分析描述项目的定位以及流程；从数学方面描述该程序的运行逻辑；从编程方面对设计进行测试，从时间角度对车流量进行分析、从图示效果对三大城市的韦恩图进行分析；好好总结，有待来者，合理解决。

**作品特色**：本设计紧紧专注于城乡车流量，既要结合数学知识、又要结合图示知识、更要结合脑图知识、还要结合编程知识、更少不了算法思想。面临多次挑战，历经长久磨炼，项目终于落地生根。既要基于简单优于复杂的原则，又要考虑到有限的经济来源，更为了有更多志同道合的伙伴参与其中，在设计上由初期的简单逐步过渡到成熟之后的复杂；基于现状进行，力求基础稳定、前期主要通过各大网络平台进行知识储备，在后期成熟阶段实践所学所得。

**简单注释**：该作品的形式为项目小组，需要注明各自职责；每一小组需要从各自选择的角度出发完成报告；报告的题目不唯一。

# 摘要

设计分别进行了微信公众号的宣传、知乎的宣传、360个人图书馆的创作、CSDN社区的实践、酷安的问答、语雀的创作、Github的应用、flomo的使用、诗词的创作、思维导图的分析、流程图的描绘、韦恩图的绘制、鱼骨图的安排、算法的呈现、大纲的展现、柱状图的计划，实现了收集、统计、分享、总结。

Apache旗下拥有众多项目，我目前了解并安装过的项目有三个，分别是Hadoop、Spark、HBase，我还想了解其它项目；我清楚地认识到既然选择了某一个项目，就要尽可能地坚持下去，而不能半途而废；学习先进的算法编程思想，和具体的应用相结合，更好地进行统计操作；目前要需要将Apache官网中陌生的英语翻译为熟悉的汉语，尽可能地了解各个项目的定位；Apache旗下产品中计算机编程占据了很大一部分，而阅读与推广的部分占据的部分应该是较少一些；据我了解，有些项目，要么尚未开发，要么就是半途而废，肯定是要引以为戒的。

昵称经历了三大阶段：第一阶段是书海遍读客，第二阶段是书读百遍者，第三阶段最终确定昵称为读书百遍者，有一个最大的目标就是数据星辰，这个目标之下有两个主流方向，一个是计算机编程，另一个是阅读与推广。

在计算机编程方面，着力研究Apache旗下的相关项目，首先要仔细阅读官网产品介绍、安装并测试相关项目，然后逐渐熟练使用旗下的开发工具及其延展工具，最后当总体使用效果达到某个程度的时候，尝试运用编程算法思想进行自我搭建、自我试用、自我安排、自我分享。

在阅读与推广方面，熟练掌握书评、影评、剧评、书摘、读法、典故、日记、故事、情节等文学样式；用好纸间书摘、Typora、纯纯写作、浮墨笔记、有诗、简讯、句读、一言、句子控、慢读等和阅读与推广密切相关的软件；信仰石家庄学院图书馆读者协会的读书、读人、读己，让阅读世界生动起来；信仰微信公众号阅享之的阅人、阅己、阅读；信仰定位本性、行路阅推。

360个人图书馆数据星辰的主页：http://lishige.360doc.com

语雀主页：https://www.yuque.com/lishige

Github主页：https://www.github.com/lishige

个人简介：https://lishige.github.io

阅读与推广：https://lishige.notion.site/945e3dc5acd741169684f7f81bfc79f2

计算机编程：https://lishige.notion.site/27b106d0bf224c13bbad7acd8155d9db

国外联系邮箱：lishige@outlook.com

国内联系邮箱：lishige@petalmail.com

我习惯于将开源免费的产品理解为落地生根，而精致付费的产品理解为能做事的做事、该发声的发声。我相信Apache旗下的产品就相当于一个基础，好比7-zip之于Bandizip、ScreenToGif之于Honeyicam、Quicklook之于Seer，Everything之于Listary Pro、OBS之于Bandicam、Honeyview之于Bandiview、Freeplane之于MindMaster、Drawio之于Edrawmax等等诸如此类。

设计介绍了需求阶段的方向、想要达到的目标、具体实现的流程、项目任务的安排以及进度步骤的控制；设计内容包括模型思想和执行逻辑，探讨了在时间维度和空间维度下车流量的变化情况，并选择了其中一个角度好好地进行了分析；依据设计的步骤进度，运用了具体的编写方法对城乡车流量的分析进行实践；储备与城乡车流量密切相关的基础知识，好好地发现执行过程中出现的问题，及时解决并做好备份。本设计能够达到根据韦恩图、柱状图分析城乡车流量的效果；功能尚处于初级阶段，仍需要结合多种国内外优秀产品继续探索更多内容，希望能够对城乡车流量的发展变化情况进行更好的可视化呈现。

【关键词】可视化产品；登录认证；国际化；模块切换

# Abstract

The design carried out the publicity of WeChat official account, Zhihu, 360 personal library creation, CSDN community practice, Ku'an Q&A, Yuque creation, Github application, flomo use, poetry creation, mind map analysis, flow chart description, Venn diagram drawing, fishbone diagram arrangement, algorithm presentation, outline presentation, histogram plan, and realized collection, statistics, sharing, and summary.

Apache has numerous projects under its umbrella. Currently, I have learned and installed three projects, namely Hadoop, Spark, and HBase. I also want to learn about other projects; I am well aware that since I have chosen a certain project, I must persist as much as possible and not give up halfway; Learn advanced algorithmic programming concepts and combine them with specific applications to better perform statistical operations; At present, it is necessary to translate unfamiliar English on the Apache official website into familiar Chinese, and try to understand the positioning of each project as much as possible; Computer programming accounts for a large portion of Apache's products, while the reading and promotion section should occupy a relatively small portion; As far as I know, some projects, either not yet developed or abandoned halfway, must be taken as a warning.

Nicknames have gone through three stages: the first stage is to read books extensively, the second stage is to read books a hundred times, and the third stage ultimately determines the nickname as a reader of books a hundred times. One of the biggest goals is the DataScienceAIStars, under which there are two mainstream directions: computer programming and reading and promotion.

In terms of computer programming, we focus on researching related projects under Apache. Firstly, we need to carefully read the product introduction on the official website, install and test the relevant projects, then gradually become proficient in using our development tools and extension tools. When the overall usage effect reaches a certain level, try using programming algorithm ideas for self construction, self trial, self arrangement, and self sharing.

In terms of reading and promotion, proficient in literary styles such as book reviews, film reviews, drama reviews, book excerpts, reading methods, allusions, diaries, stories, and plots; Make good use of software closely related to reading and promotion, such as paper-based book picking, Typora, PureWriter, inkjet notes, poetry, text messages, sentence reading, one word, sentence control, slow reading, etc; Believing in the reading, reading people, and reading oneself of the Shijiazhuang University Library Reader Association, making the reading world more vivid; Believe in the people, self and reading enjoyed by WeChat official account; Belief positioning, nature, and travel recommendations.

360 Personal Library DataScienceAIStars homepage: http://lishige.360doc.com

Yuque homepage: https://www.yuque.com/lishige

Github homepage: https://www.github.com/lishige

Personal profile: https://lishige.github.io

Reading and promotion：https://lishige.notion.site/945e3dc5acd741169684f7f81bfc79f2

Computer programming ：https://lishige.notion.site/27b106d0bf224c13bbad7acd8155d9db

Foreign contact email: lishige@outlook.com

Domestic contact email: lishige@petalmail.com

I am accustomed to understanding open-source and free products as rooted, while exquisite and paid products are understood as things that can be done and things that should be said. I believe that Apache's products are equivalent to a foundation, such as 7-zip to Bandizip, ScreenToGif to Honeyicam, Quicklook to Seer, Everything to Listary Pro, OBS to Bandicam, Honeyview to Bandiview, Freeplane to MindMaster, Drawio to Edrawmax, and so on.

The design introduces the direction of the requirements phase, the goals to be achieved, the specific implementation process, the arrangement of project tasks, and the control of progress steps; The design content includes model ideas and execution logic, explored the changes in passenger flow in both time and space dimensions, and selecting one angle for thorough analysis; Based on the progress of the design steps, specific writing methods were applied to practice the analysis of urban and rural traffic flow; Reserve basic knowledge closely related to urban and rural traffic flow, identify problems that arise during the execution process carefully, solve them in a timely manner, and make backups. This design can achieve the effect of analyzing urban and rural traffic flow based on Wayne diagrams and bar charts; The functionality is still in its early stages and further exploration is needed by combining various excellent domestic and foreign products. It is hoped that better visualization of the development and changes in urban and rural traffic flow can be achieved.

[Keywords] Visual products; Login authentication; Internationalization; Module switching

# 目录

|   主流   | 分支 |
| :------: | :--: |
|   信息   |      |
|   摘要   |      |
| Abstract |      |
|   目录   |      |
|   引言   |      |
|          | 背景 |
|          | 简介 |
|   报告   |      |
|          | 概述 |
|          | 概论 |
|          | 计划 |
|          | 流程 |
|          | 思想 |
|          | 限制 |
|          | 思考 |
|          | 对比 |
|          | 分析 |
|          | 环境 |
|          | 要点 |
|          | 测试 |
|          | 问题 |
|          | 评价 |
|          | 结果 |
|          | 结论 |
|          | 其它 |
|          | 建议 |
|   结语   |      |
|   文献   |      |
|   附录   |      |
|   致谢   |      |

# 引言

## 一、背景

自行车、三轮车、电动车、公交车、卡车、汽车、火车、飞机等交通工具在生活中都是非常常见的。此类交通工具对于社会的和谐与稳定起到了十分重要的作用。设计由学院内志同道合的有缘人组成，办公场地为学校孵化园；设计有利于增强各方面的社会实践。

对数据信息进行统计、遵循一定的变化规律、按照一定的分析模型，准确判断城乡车流量的发展方向，描绘出城乡车流量未来的走势。

## 二、简介

> 五星红旗下英雄，数据星辰前看客。儒山脚下，北洺河上，三清阁旁，寺庙之间；遥望宇宙，日月轮回，群星无数，星月相依。黄河地上串黄河，泰山庙中敬孔子，关羽庙下拜关圣，奶奶庙旁烧元宝，土地爷前行路人，风雨之中见八戒，六边形内现蟒蛇，一杯浓茶忘财神。想佛祖，思菩萨，读书百遍者，人间普通人。

车流量项目的设计、开发与测试为方向，以巩固与交通大数据相关的基础知识、提高管理效率、增强出行便捷性、促进经济的高速发展、促进稳定发展提供更多的发展空间为目标。

# 报告

> 我可以毫不客气地这样说，正是因为有了这个基金会的存在，所以才能享受到精致高效的压缩、才能领略到精美快速的脑图、才能感受到独到稳定的图创、才能体验到流利动人的录制；mm、gif、png、svg等软件后缀肯定和Apache这个组织密切相关。

![《基于Apache的城乡车流量回顾、在线、展望模型的设计与开发》飞机](https://img.picgo.net/2024/03/30/Apachee51ec878df4fcb60.jpeg)

[![Apache Software Foduntion(Apache软件组织)](https://img.picgo.net/2024/03/30/Apache-Software-FoduntionApacheb791f8b82f217e3e.png)](https://www.picgo.net/image/SGUut2)

## 一、概述

### ㈠官网

![Apache官网二维码](https://img.picgo.net/2024/03/30/Apache67f1e271c7f6af87.png)

### ㈡主页

![Apache的Github主页](https://img.picgo.net/2024/03/30/ApaheGithubbc06f8a8d660e741.png)

这个主页在Gihub搭建的，有大量的开发者参与其中，共同捍卫着开源软件的发展进程。

### ㈢标识

#### ⑴ASF

![ASF](https://img.picgo.net/2024/03/30/ASFbd93e48c37adf4bf.png)

ASF是 Apache Software Foundation的简称。

#### ⑵羽毛

![ASF1999](https://img.picgo.net/2024/03/30/ASF1999497cc22c34e68185.png)

图标展现了Apache基金会的创建时间始于1999，整体显得简洁、优雅、大方、得体。

#### ⑶会徽

![TheApacheWay](https://img.picgo.net/2024/03/30/TheApacheWay2d4aa807bad969b1.png)

The Apache Way(我觉得这个会徽应该理解为Apache自己处理问题和解决问题的方式)

### ㈣横幅

公益软件测试

software for the public good test

### ㈤成就

ASF 的开源软件在世界各地无处不在，超过 8,400 名提交者为 320 多个活跃项目做出了贡献。

ASF’s open source software is used ubiquitously around the world with more than 8,400 committers contributing to more than 320 active projects.

### ㈥职责

ASF是一个慈善组织，几乎完全由志愿者运营，他们负责监督数百个项目。我们的赞助商使我们能够维护支持他们所需的基础设施。

The ASF is a charitable organization run almost exclusively by volunteers who oversee hundreds of projects. Our sponsors enable us to maintain the infrastructure needed to support them.

### ㈦项目

#### ⑴官网

![Apache项目二维码](https://img.picgo.net/2024/03/30/Apache4b1788fa02c7b992.png)

#### ⑵横幅

欢迎来到 Apache 项目目录

Welcome to the Apache Projects Directory

#### ⑶介绍

基础设施、差旅协助、安全团队、法律事务和品牌管理

请注意，此处显示的信息依赖于鼓励 PMC 提供的 DOAP 文档。然而，DOAP 不是强制性的，并非所有 PMC 都为其管理的所有项目提供了 DOAP。

此站点是 Apache Software Foundation 项目的目录。它旨在帮助您找到符合您兴趣的特定项目，并更广泛地了解 Apache 社区中当前正在进行的各种工作。

目前 ASF 有 TBA 开源计划：⑴TBA委员会管理TBA项目⑵5个特别委员会⑶TBA孵化豆荚。

Infrastructure, Travel Assistance, Security Team, Legal Affairs and Brand Management.

Please note that the information displayed here relies on the DOAP files which PMCs are encouraged to provide. However DOAPs are not mandatory, and not all PMCs have provided a DOAP for all the projects they manage.

This site is a catalog of Apache Software Foundation projects. It is designed to help you find specific projects that meet your interests and to gain a broader understanding of the wide variety of work currently underway in the Apache community.

There are currently TBA open source initiatives at the ASF:⑴TBA committees managing TBA projects⑵5 special committees⑶TBA incubating podlings.

#### ⑷分类

| 字母 | 项目一                                                       | 项目二                                                       |
| :--- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| a    | Accumulo、ActiveMQ、AGF、Airavata、Airflow、Alutra、Ambari、Ant、APISX、Aries、Arrow、AsterixDB | Atlas、Attic、Avro、Axis                                     |
| b    | Beam、Bigtop、Bloodhound、BooKeeper                          | Brooklyn、bRPC、BuildStream、BVal                            |
| c    | Calcite、Camel、CarbonData、Cassandra、Causeway、Cayenne、Celeborn | Celix、CloudStack、Cocoon、Commons、Community Development、Cordova、CouchDB、Creadur、cTAKES、Curator、CXF |
| d    | Daffodil、DataFu、DataSketches、DB、DeltaSpike、Directory、DolphinScheduler | Doris、Drill、Druid、Dubbo、                                 |
| e    | Echarts                                                      | Empire-db、EventMesh                                         |
| f    | Felix、Fineract、Flagon、Flex                                | Flink、Fluo、FreeMarker                                      |
| g    | Geode、Geronimo、Gobblin、Gora                               | Griffin、Groovy、Guacamole、Gump                             |
| h    | Hadoop、HAWQ、HBase、HelixHive、Hop、HTTP Server             | HttpComponents、Hudi                                         |
| i    | Iceberg、Ignite、Impala、Incubator                           | Inlong、IoTDB                                                |
| j    | James、jclouds、Jena、JMeter                                 | Johnzon、JSPWiki、Juneau                                     |
| k    | Kafka、Karaf、Kibble、Knox                                   | Kudu、Kvrocks、Kylin、Kyuubi                                 |
| l    | Libcloud、Linkis、Logging Services                           | Lucene、Lucene.Net                                           |
| m    | MADlib、Mahout、ManifoldCF、Maven、Mesos、MINA、Mnemonic     | mod_perl、MyFaces、Mynewt                                    |
| n    | NETBeans、NiFi                                               | Nutch、NuttX                                                 |
| o    | OFBiz、Olingo、Oozie、OpenDALOpenJPA、OpenMeetings           | OpenNLP、OpenOffice、OpenWebBeans、OpenWhisk、ORC、Ozone     |
| p    | Paimon、Parquet、PDFBox、Pekko、Phoenix、Pig                 | Pinot、PLC4X、POI、Portable Runtime、Portals、Pulsar         |
| q    | Qpid                                                         |                                                              |
| r    | Ranger、Ratis、RocketMQ                                      | Roller、Royale、Ra                                           |
| s    | Samza、Santuario、SeaTunel、Sedona、Serf、ServiceComb、ServiceMix、ShardingSphere | ShenYu、Shiro、SINGA、SIS、SkyWalking、Sling、Solr、SpamAssassin、Spark、Steve、Storm、StreamPipes、Streams、Struts、Submarine、Subversion、Superset、Synapse、Syncope、SystemDS |
| t    | Tapestry、Tcl、Tez、Thrift、Tika、TinkerPop、Tomcat、TomEE、Traffic Control | Traffic  Server、TsFile、Turbine、TVM                        |
| u    | UIMA、Uniffle(Incubating)、                                  | Unomi                                                        |
| v    | VCL、Velocity、Velocity DVSL、Velocity Tools、VSS Ant Library | VXQuery(in the Attic)、Vysper                                |
| w    | Wayang(Incubating)、Websh、Whimsy、Whirr(In the Attic)、Whisker、Wicket | Wink(in the Attic)、Woden、Wookie(in the Attic)              |
| x    | Xalan for C++ XSLTProcessor、Xalan for Java XSLTProcessor、Xerces for C++ XML Parser、Xerces for Java XML Parser、Xerces for Perl XML Parser | Xindice(in the Attic)、XML Commons External、XML Commons Resolver、XML Graphics Commons、XMLBeans、XTable(Incubating) |
| y    | Yetus                                                        | YuniKorn                                                     |
| z    | Zeppelin                                                     | ZooKeeper                                                    |

## 二、概论

### ㈠要求

1. 尽量使用数据耦合：依赖关系变得简洁明了，可以降低复杂性、可以提高可维护性、可以提高可重用性、可以提高灵活性；建议设计清晰的接口，建议使用数据结构来传递参数。
2. 少用控制耦合：控制耦合对系统的修改工作不利，可以降低模块间的关联度，提高模块的独立性。
3. 限制公共耦合：减少模块的耦合度，提高模块的可维护性；建议合理设计模块间的接口，建议使用数据封装和抽象来降低公共耦合。
4. 绝对不用内容耦合：增加了脆弱性，可能导致连锁反应；违反了面向对象设计中的封装原则，降低了有效性和可靠性。

### ㈡目标

1. 设计并创建出基本框架：明确定位、明确目标、明确方面、坚定立场、划分模块、提高效率、性能优化。
2. 实现各页面之间的参数传递以及简单逻辑页面的跳转：在页面间参数传递方面，可以通过URL参数传递、可以使用本地存储、可以使用服务器端会话；在简单逻辑页面的跳转方面，使用HTML的<a>标签、服务器端重定向。
3. 为特定界面中的按钮添加功能：确定按钮类型、明确点击按钮后的操作、创建HTML结构、为按钮添加事件监听器。
4. 把页面元素封装并将其抽象出来以实现页面动态订制：可以定义页面结构、可以创建组件库、可以使用属性传递、可以构建页面模板、可以实现动态定制逻辑。
5. 简单交互：可以使用HTML结构、可以使用CSS样式、可以使用JavaScript交互。

### ㈢进度

报告可以分为十八个模块：概述、概论、计划、流程、思想、限制、思考、对比、分析、环境、要点、测试、问题、评价、结果、结论、其它、建议。

| 分类 | 内容介绍                                                     |
| :--: | ------------------------------------------------------------ |
| 概述 | 介绍了Apache这个开源项目的官网、主页、标识、横幅、成就、职责和项目七大部分，其中标识可以分为三大类，分别是ASF、羽毛和会徽，而项目可以分为官网、横幅、介绍和分类四大类。 |
| 概论 | 描述了进行城乡车流量回顾、在线与展望的要求、目标和进度三大部分。 |
| 计划 | 城乡车流量的回顾、在线、与展望的时间任务可以分为时间安排、时间特征、时间转换和时间配置四大部分，其中时间安排可以分为时间函数和和日期函数两大类，而时间特征可以分为相对性、绝对性、一维性、同时性和均匀性五大类，再者时间转换可以分为转换出小时、转换出星期、转换出月份、语句被操作四大类。 |
| 流程 | 启动城乡车流量执行流程需要考虑到数据精确度、数据通信度和数据适应性三大类。 |
| 思想 | 在搭建城乡车流量模型的时候，分别探讨了随机森林模型和线性回归模型这两个部分，其中随机森林模型研究了随机森林的定义、基本算法思想、单颗决策之树、集成学习模型这四大类，而线性回归模型研究了线性回归定义、总体回归分析、随机误差性质这三大类。 |
| 限制 | 城乡车流量模型的回顾、在线、展望受到冒泡排序、选择排序、插入排序和快速排序四大排序算法的限制，分别对四大排序算法进行了代码呈现和算法可视化。 |
| 思考 | 分别从时间维度、空间维度、环境维度、经济维度、其它维度讨论了城乡车流量模型执行过程中存在的问题以及解决办法，深究了Apache旗下的项目几个算法思想具体配置，对于如何更好地促进城乡车流量的发展提出了自己在学习方面的建议。 |
| 对比 | 以三大区域韦恩图和三大区域柱状图的形式对邯郸、石家庄、天津的汽车车流和飞机车流进行了对比；在三大区域韦恩图方面，从时间维度、空间维度、城市车流、梳理知识四大角度进行了讨论；在三大区域柱状图方面，从一星期之内的变化情况这个角度出发，分别将邯郸、石家庄、天津三大区域车流量的变化情况与这三大区域城乡车流量的变化情况进行了对比；对于城乡车流量的早晚期、高峰期、低谷期这三个时期进行了更细致的、更深入的梳理。 |
| 分析 | 主要对汽车车流和飞机流量进行了分析。在汽车车流方面，先了解了具体流程，然后进行了情况分析；在具体执行流程方面，分别描述了如何统计形成、如何进行特征转换、如何显示统计结果；在情况分析方面，分别从汽车车流的波动情况、普通汽车与公交汽车的比对、司机乘客各司其职各就其位三大角度进行了剖析。在飞机流量两方面，分为统计、比较、总结三大过程；按照日期对于飞机流量进行了统计；将白天和夜晚飞机的流量进行了比较；将飞机的总体流量和变化情况进行了总结。 |
| 环境 | 整理了在讨论城乡车流量变化情况时所使用的设备以及设备的配置情况。 |
| 要点 | 明确了安装测试、基本步骤、测试方法、测试要求、测试原则这五大要点，分别对五大要点进行了详细的说明。 |
| 测试 | 在测试方面，分为测试定位、测试内容、测试要求、测试进度四大步骤。 |
| 问题 | 深究了在讨论城乡车流量变化情况时遇到的障碍问题，以及障碍的解决办法，以及由此得到的经验教训。 |
| 评价 | 对测试的情况进行了评价，提出了测试需要坚持的七大准则，分别是：完整性准则、独立性准则、有效性准则、可重复性准则、及时性准则、可追溯性准则、文档化准则。 |
| 结果 | 从车流情况、项目研究、工具使用、环境搭建、数据测试这几个角度进行了总结。 |
| 结论 | 从算法思想、代码实现、图示呈现、高峰低谷、车流展望这几个角度进行了阐发。 |
| 其它 | 从目的、特征、比较、总述四个方面对城乡车流量变化的实际情况和城乡车流量变化遇到的具体概念进行了额外补充。 |
| 建议 | 对城乡车流量的研究情况进行了总结，对如何更加强城乡车流量的研究提出了自己的倡议。 |



## 三、计划

![城乡车流量计划](https://img.picgo.net/2024/04/06/0aaf2c7fa64617b5906d789c962ff0c1c03a132df3b4b93f.png)

### ㈠时间安排

时间转换函数：将时间格式转换为另一种时间格式的函数。

#### ⑴时刻函数

1. **TIME 函数**：生成指定时间。
2. **HOUR 函数**：提取时间中的小时数。
3. **MINUTE 函数**：提取时间中的分钟数。
4. **SECOND 函数**：提取时间中的秒数。

#### ⑵日期函数

1. **NOW函数**：获取当前的时刻。
2. **TODAY函数**：获取当天的日期。
3. **DAY函数**：获取日期中的天数。
4. **WEEKDAY函数**：根据日期返回星期对应的数字。
5. **MONTH函数**：获取日期中的月份。
6. **EOMONTH 函数**：向上求取指定月份前面或后面的最末一天的日期。
7. **YEAR函数**：求得日期中的年份。
8. **DATE 函数**：求取一个指定的日期。
9. **DATEDIF函数**：求得两日期存在的差值。

### ㈡时间特征

#### ⑴相对性

1. 随着物质相对运动的产生而产生，随着物质相对运动的终止而终止。
2. 与相对运动有关，只要物质之间没有产生相对运动，那么就不会有时间的存在。
3. 并不是物质，它只是物质的表现形式，时间是由物质的空间运动产生的，没有运动就没有时间。

#### ⑵绝对性

1. 是绝对的，没有绝对不运动的物质。
2. 人每时每刻都能感受到时间在不同地流逝，只有专注于某一件事情，才会发现时间静止了。
3. 有运动必然有物质。
4. 有物质必然有时间。

#### ⑶一维性

1. 空间运动的表现形式。
2. 空间位置发送随着远近次序的变化而产生。
3. 由空间中的相对运动决定。

#### ⑷同时性

1. 不同的物质个体都拥有自己的时间。
2. 不同的参考系具有各不相同的运动。
3. 必须确定一个时间基准。

#### ⑸均匀性

1. 物质世界存在普遍联系。
2. 每一事物时时刻刻都受到周围其它事物的作用。
3. 绝对均匀的运动在宇宙中可并不存在。

### ㈢时间转换

#### ⑴转换出小时

使用运算表达式将原始数据比如秒、分钟、周、月等转换为小时，可以使用相关函数进行转换运算。

#### ⑵转换出星期

输入与星期有关的文本，遵循符号规则，查看可视化效果，进行转换。

#### ⑶转换出月份

月份与周和星期的联系很紧密；依据使用习惯，输入需要读取的时间数据，将修改后与月份相关联的数据插入，输出前查看可视化效果，确保数据的准确性，最后进行输出操作。

#### ⑷语句被操作

使用的相关语句既有与编程相关的输入输出操作，也有可视化操作。

### ㈣时间配置

#### ⑴启动

进行调查，深入了解变化情况。

#### ⑵立项

进行任务分配，由各个功能的参与者共同完成。

#### ⑶开发

进行功能方面的测试，对逻辑流程进行梳理，对代码进行整理，代码应符合高质量编程规范的相关要求。

#### ⑷发展

了解整体流程以及整体功能，采用合适的测试方式来进行实践和检测，在合适的范围内，进行测试。

## 四、流程

![城乡车流量执行流程](https://img.picgo.net/2024/03/30/7849c6b3aec7bfb51cd25acf81b69b54c63401e0be32de99.png)

城乡车流量分析涉及内容广泛，进行车流分析，可以分为运用手段、应用场景、车流分析、使用模型四大部分。

### ㈠数据精确度

1. 输入输出精度的要以小数点为单位。
2. 传输精度的要求也要以小数点为单位 。
3. 理清精准与粗略的关系。

### ㈡数据通信度

1. 通信之时要提前声明、你情我愿、谨言慎行、自省自渡、自问自答、自己解决。
2. 夹缝生存、夹缝求信、信字保明、流动坚持。
3. 以各种工具为媒介，采用基本的沟通方式，建立沟通机制、建立反馈机制。
4. 保证数据的精确度和可靠性。
5. 考虑通信双方的利益、建立互信关系、争取实现双赢。
6. 尊重各自的立场和观点。
7. 保持开放的心态。
8. 接纳不同的意见。

### ㈢数据适应性

1. 城乡车流量与我们的生活密切相关。
2. 交通工具在挨家挨户、大街小巷随处可见。
3. 街道上交通工具来往频繁，熙熙攘攘。
4. 应当考虑到天气、节假日、交通事件等具有代表性的情况。
5. 应当通过数据清洗等方法处理噪声和异常值。
6. 分析车流量的时空分布特征；应当处理交通堵塞瓶颈。
7. 各种车流状态趋于稳定趋势。

## 五、思想

### ㈠探讨随机森林模型

![森林汽车](https://img.picgo.net/2024/03/30/9af4723a2b18bfd4d96a8e43954e2c237e3d2dd09722ff2d.png)

#### ⑴随机森林定义

随机森林模型是一种集成学习算法，由多个决策树组成，利用多个决策树对样本数据进行训练、分类和预测，可以处理高维数据，模型的泛化能力强，可以处理不平衡数据，平衡误差，结果准确度很高。

#### ⑵基本算法思想

1. **随机森林算法**：是一种新的机器学习模型，非线性基于树的模型，集群分类模型的一种；随机森林由很多的决策树组成，而且每一棵决策树之间是没有关联的。由决策树作为弱学习器组成的森林模型为随机森林模型，简称为随机森林。
2. **新型装袋算法**：装袋算法基于自助采样法，通过对原始数据集进行有放回的随时采样，构建出多个不同的子集；此模型基于集成学习方法构造,所以训练构造的过程基本上也遵从集成学习的基本流程。

#### ⑶单棵决策之树

1. **自助之法**：又称为自助抽样法，通过自助法确定的训练样本集，是一种有放回的均匀抽样。
2. **特征集合**：从当前集合中选取几个特征组成新的特征集合，可以是数值型的、类别型的，需要考虑相关性、冗余性、可解释性鲁棒性。
3. **样本子集**：分别对样本数据集进行计算，确定最优特征切分点，将样本分配到子结点所对应的样本子集中，用到的选择方法有随机抽样、分层抽样、聚类抽样。
4. **指数算法**：以指数函数为基础，通过幂运算的方式进行计算。

#### ⑷集成学习模型

1. **定位**：并不是一个单独的机器学习算法，通过构建并结合多个机器学习器来完成学习任务，是一种机器学习范式。
2. **思想**：将多个模型的预测结果结合起来，达到更好的分类效果。
3. **内容**：可以分为平均法和投票法；平均法将多个模型的预测结果取平均值，用于回归问题的解决；投票法将多个模型的预测结果进行投票，选择票数最多的类别作为最终预测结果。
4. **作用**：降低误差和提高准确率，提高模型的稳定性，减少过拟合和欠拟合的风险，提高泛化能力。

### ㈡探讨线性回归模型

![火箭发射](https://img.picgo.net/2024/03/30/2ba0f227b2bf38432caf30849e8aa462b4bf4dad55d87472.png)

#### ⑴线性回归定义

探索因变量和自变量或解释变量和被解释变量之间的线性关系，是一种预测性的建模技术；分为线性关系、误差最小化、模型参数、解释性、局限性。

#### ⑵总体回归分析

用于揭示两个或多个变量之间的平均关系，通过数据收集和数据分析来进行推断和预测，可以解释一个变量如何影响另一个变量。

#### ⑶随机误差性质

**随机误差**：随机误差出现的机会是均等的；随机误差出现的概率相同；随机误差的大小和方向是不确定的，无法提前预知或避免；随机误差也称为偶然误差或不定误差，是一种随机波动；随机误差的影响因素有室温、相对湿度、气压；随机误差的大小和正负都不固定。

1. **忽略**：误差在统计上相互独立、分布均匀，误差对于总体模型的影响是微小的。
2. **观测**：通过多次测量取平均值的方法来减小随机误差的影响。
3. **设定**：基于相同的观测条件下，对某一变量进行多次观测。
4. **手段**：控制温度的变化情况、提高设备的精度限制、优化操作者的微小差异。

## 六、限制

以每秒、每分钟、每小时、每年度为单位，以城乡车流量变化情况为总体研究方向，以冒泡排序、选择排序、插入排序为、快速排序四大排序算法为基础进行代码实现和排序可视化。

### ㈠冒泡排序

#### ⑴代码的呈现

```java
package SortingAlgorithm;

public class BubbleSort
{

    public static void main(String[] args)
    {
        int[] array = {6,3,4,0,7,8,5,9,2,1};
        BubbleSort bubblesort = new BubbleSort();
        bubblesort.bubbleSort(array);
        bubblesort.showArray(array);
    }

    public static void bubbleSort(int[] arr)
    {
        int n = arr.length;
        for (int i = 0; i < n - 1; i++)
        {
            for (int j = 0; j < n - i - 1; j++)
            {
                if (arr[j] > arr[j + 1])
                {
                    // 交换 arr[j] 和 arr[j + 1]
                    int temp = arr[j];
                    arr[j] = arr[j + 1];
                    arr[j + 1] = temp;
                }
            }
        }

    }
    public void showArray(int[] arr)
    {
        for(int i:arr)
        {
            System.out.print(i+" ");
        }
    }
}
```

```python
def bubble_sort(arr):
    n = len(arr)
    for i in range(n-1):
        for j in range(n-i-1):
            if arr[j]>arr[j+1]:
                arr[j],arr[j+1] = arr[j+1],arr[j]
array=[6,3,4,0,7,8,5,9,2,1]
bubble_sort(array)
for i in range(len(array)):
    print(array[i])
```

#### ⑵算法可视化

[![冒泡排序](https://img.picgo.net/2024/03/30/e5c25803ec3dfa7201b0eb5f5085ace8500b342810120a16.png)](https://www.picgo.net/image/SGUDYN)

### ㈡选择排序

#### ⑴代码的呈现

```java
public class SelectionSort
{
    public static void main(String[] args)
    {
        int[] array={45,32,14,54,23};
        SelectionSort selectionsort = new SelectionSort();
        selectionsort.selectionSort(array);
        selectionsort.showArray(array);
    }
    public static void selectionSort(int[] arr)
    {
        int n = arr.length;
        for(int i=0;i<n-1;i++)
        {
            int min_idx=i;
            for(int j=i+1;j<n;j++)
            {
                if (arr[j]<arr[min_idx])
                {
                    min_idx=j;
                }
            }
            int temp = arr[min_idx];
            arr[min_idx]=arr[i];
            arr[i]=temp;
        }
    }
    public void showArray(int[] arr)
    {
        for(int i:arr)
        {
            System.out.print(i+" ");
        }
    }
}
```

```python
def selection_sort(arr):
    n = len(arr)
    for i in range(n-1):
        min_idx = i
        for j in range(i+1,n):
            if arr[j] < arr[min_idx]:
                min_idx = j
        arr[i],arr[min_idx] = arr[min_idx],arr[i]
array=[45,32,14,54,23]
selection_sort(array)
for i in range(len(array)):
    print(array[i])
```

#### ⑵算法可视化

![选择排序](https://img.picgo.net/2024/03/30/5268e9ec7de83e9a9ef3e88390b3ebe471cb2c3eab802e05.png)

### ㈢插入排序

#### ⑴代码的呈现

```java
public class InsertionSort
{
    public static void main(String[] args)
    {
        int[] array = {42,20,17,13,28,14,23,15};
        InsertionSort insertionsort = new InsertionSort();
        insertionsort.insertionSort(array);
        insertionsort.showArray(array);
    }
    public static void insertionSort(int[] arr)
    {
        int n=arr.length;
        for(int i=1;i<n;i++)
        {
            int key = arr[i];
            int j=i-1;
            while(j>=0 && arr[j]>key)
            {
                arr[j+1]=arr[j];
                j=j-1;
            }
            arr[j+1]=key;
        }
    }
    public static void showArray(int[] arr)
    {
        for(int i=0;i<arr.length;i++)
        {
            System.out.print(arr[i]+" ");
        }
    }
}
```

```python
def insertion_sort(arr):
    n = len(arr)
    for i in range(1,n):
        key = arr[i]
        j = i - 1
        while j>= 0 and arr[j] > key:
            arr[j+1] = arr[j]
            j-=1
        arr[j+1] = key
array = [42,20,17,13,28,14,23,15]
insertion_sort(array)
for i in range(len(array)):
    print(array[i])
```

#### ⑵算法可视化

![插入排序](https://img.picgo.net/2024/03/30/8ef4eac7025e62a91ab36231f83150b97eb52776a8cc2c7c.png)

### ㈣快速排序

#### ⑴代码的呈现

```java
public class QuickSort
{
    public static void main(String[] args)
    {
        int[] array={4，7，6，5，3，2，8，1};
        int n = array.length;
        QuickSort quicksort = new QuickSort();
        quicksort.quickSort(array,0,n-1);
        quicksort.showArray(array);
    }
    public static void quickSort(int[] arr,int low,int high)
    {
        if(low<high)
        {
            int pivotIndex = partition(arr,low,high);
            quickSort(arr,low,pivotIndex-1);
            quickSort(arr,pivotIndex+1,high);
        }
    }
    public static int partition(int[] arr,int low,int high)
    {
        int pivot = arr[high];
        int i=low-1;
        for(int j=low;j<high;j++)
        {
            if (arr[j] <= pivot)
            {
                i++;
                int temp = arr[i];
                arr[i] = arr[j];
                arr[j] = temp;
            }
        }
        int temp  = arr[i+1];
        arr[i+1]=arr[high];
        arr[high]=temp;
        return i+1;
    }
    public static void showArray(int[] arr)
    {
        for(int i=0;i<arr.length;i++)
        {
            System.out.print(arr[i]+" ");
        }
    }
}
```

```python
def quick_sort(arr):
    if len(arr) <= 1:
        return arr
    pivot = arr[len(arr) // 2]
    left = [x for x in arr if x < pivot]
    middle = [x for x in arr if x == pivot]
    right = [x for x in arr if x > pivot]
    return quick_sort(left) + middle + quick_sort(right)
array = [4，7，6，5，3，2，8，1]
sorted_arr=quick_sort(array)
for i in range(len(sorted_arr)):
    print(sorted_arr[i])
```

#### ⑵算法可视化

![快速排序](https://img.picgo.net/2024/03/30/0c703b37d30adb1f709048948827dd755633a14d1dcd08aa.md.png)

## 七、思考

### ㈠发现问题

**时间维度**：在节假日期间，车流量频繁；而在平常时间，几乎没有车流量；在旅游区，车流量聚集于某一段时间内，过了这段时间，就变得冷冷清清。

**空间维度**：城市车流量处于较高状态，人口流密度大，道路两旁到处都是停着的汽车，偶尔会见到电动车或三轮车；乡村车流量处于中等状态，门口、路口、停车地带停满了车辆，给人们的出行带来了不方便，经常会看到乱停车的现象。

**环境维度**：道路两旁随处可见乱扔的垃圾；车流量不断上升，导致温度长时间变暖，很难体验到冬天的新鲜感。

**经济维度**：最流行的当属小汽车，家家户户都会出钱购买汽车；城乡交叉地带卡车来往最频繁；公路使用时间很长，缺少维修，有的路段已经开裂；在公路的交叉口经常看到停车卖水果蔬菜的人，这样的买卖很少有人光顾，几乎无人搭理；加油站的活动除了洗车和送卫生纸之外没有其它更新的活动。

**其它维度**：使用的频率汽车过于频繁，使得温度变暖、气温升高，间接破坏了春夏秋冬的自然规律；到处出现乱停车的现象，甚至还占用别人的空间，街道和道路显得十分拥挤。

### ㈡解决问题

**时间维度**：在较近的区域内不建议使用交通工具；不要把车流量都聚集于某一节假日，可以选择平常合适的时刻开车去旅游区散散心，了解一下旅游区或行车周围空气的温度湿度，对出现的异常想想解决办法。

**空间维度**：多出去走动，感受新鲜的空气，不应该只是依靠汽车；找好停车的位置，考虑到周围人的利益。

**环境维度**：关注汽车的出气口，增加尾气排放的处理办法。

**经济维度**：以实际经济实力购买汽车，而不能过度依赖于贷款；依据使用途径和使用习惯来选择适合自己的交通工具，不要只图一时的新鲜感。

**其它维度**：将汽车驾驶频率控制在合适的范围之内，多出去走动；熟悉交通环境和交通规则，可以减少出行花费的时间；定期坚持交通工具的各个工农，较少交通事故的发生。

### ㈢关联内容

Apache算法有Apacheout算法、Apache Spak MLlib算法、Aapache Flink、Apache Strom等。

1. **Apache Flink**：支持高吞吐、低延迟、高性能，是分布式流式数据处理框架。

2. **Apache Storm**：提供了高可靠性、容错性强的计算框架，是一个开源的、分布式的实时计算系统。

3. **Apache Mahout**：可以实现聚类、分析、推荐、顾虑、频繁子项挖掘。

4. **Apache Spark MLlib** ：可以简化大规模数据的机器学习任务，可以用于分类、回归、聚类、推荐、降维等任务。

### ㈣经验教训

**学习建议**：多了解Apache旗下的更多项目，首先最要紧的是将陌生的它国语言翻译为熟悉的汉语，了解已经产生或者将要产生的项目，进行Apache旗下产品的创造性推广，激发更多的志同道合者矢志不渝地参与到开源项目的维护中来；熟悉汽车驾驶技术，当好辅助主架的副驾，提高对于道路两盘以及道路前方交通设施的关注度。



## 八、对比

### ㈠三大区域韦恩图

![城乡车流量韦恩图](https://img.picgo.net/2024/03/30/3053c8e02bf7058faf8fc482ea06dc3ac00df82e85e78641.png)

#### ⑴时间维度

石家庄、邯郸、天津为三大区域的作息时间整体趋于稳定状态，总觉得车流来往过于频繁，日子过得很快，日子总是稍纵即逝；在上午时刻，很少有车流的走动，车辆要么停于停车区域，要么停于停车场，要么停于自家门口；在下午时刻，飞机车流仅仅只有一两次流动；铁路、公路、高铁的设置大大减少了提高了出行的效率，缩短了步行时所用的时间；早出晚归的行车作息很稳定；早晚高峰期并不明显，车流量都很密集，高峰时段车流量变化和低谷时段车流量变化并不明显。

#### ⑵空间维度

邯郸地区上方偶尔见到飞来飞去的飞机，邯郸公路上的车流密集，到处都是来来往往的载着众多货物的卡车，卡车占据了公路的大部分区域，而家用汽车的流动相对而言比较灵活一些，邯郸乡村里经常见到你来我往的电动车和三轮车；石家庄作为省会城市，沟通了河北众多区域之间的关系，到处都是朝着石家庄前进的车流，公路、铁路、高铁设置整洁方便，解决了公路车流拥挤的问题；在天津地区的出行效率肯定与邯郸、石家庄不相上下，铁路与高铁交相呼应，汽车车流必定如同你方唱我登场；城乡车流量的回顾、在线与展望可以为三大城市进行更好的沟通提供一种崭新的解决方案。

#### ⑶城乡车流

城市的流动区域狭窄，而乡村的流动区域广泛；城市到处都是密集的车流，而乡村到处都是独行的车流；城市中的汽车停在停车区域或停车场，而乡村中的汽车都停在自家门口；飞机运行从城市起步，而在乡村只能抬头仰望廖若晨星的飞机。

#### ⑷梳理知识

希望可以在邯郸回顾《基于Spark的城市车流量模型的设计与开发》这篇设计，要有九牛一毛莫自夸，骄傲自满必翻车的反省精神，反思存在的问题，寻找不足之处；希望可以在石家庄在线应用《基于Spark的城乡车流量模型的设计与开发》这篇设计，要有过往不恋、未来不迎、当下不杂、逆来顺受的思想；希望可以在天津展望《基于Apache的城乡车流量模型的设计与开发》这篇设计，要拥有芝麻开花节节高的思想，创新该创新的，舍弃该舍弃的，一步一个台阶，步步为营；总结的形式分为两种，第一种是《城乡车流量回顾、在线、展望模型的设计与开发》之原版与修改，第二种是《城乡车流量回顾、在线、展望模型的设计与开发》之回顾、在线、展望；所有的研究成果统称为《城乡车流量回顾、在线、展望模型的设计与开发》。

### ㈡三大区域柱状图

汽车和飞机等都是生活中常用的交通出行工具，实用性很强，很有必要了解两者之间的共性与区别，更好地促进城乡车流量的发展。

![城乡车流量柱状图](https://img.picgo.net/2024/03/30/b73a8f361b9b96b5dff49a56e1f726b17465a7183b15388b.png)

从柱状图的变量情况来看，一星期之内，三大区域的车流量变化处于稳定状态，中间稍有不明显的波动情况发生。城市车流量是邯郸、石家庄和天津这三大城市的平均值；每个城市的车流量变化都不相上下；邯郸在一星期之内的变化并不是很明显，当地的发展趋势也处于很好的状态；石家庄作为省会城市，很容易看出处于很高的发展状态；天津本来就是一个发展很好的城市，城市车流量基本上处于一个稳定的状态。

| 订单信息 | 简单介绍                                                     |
| :------: | :----------------------------------------------------------- |
|   日期   | 车辆订单的数据变化和所处的日期有很大的关系，并且会随着日、周、月、年进行变化；节假日的订单会很密集，其它时刻订单的数据会很稀疏。 |
|   收入   | 车辆订单的收入和时间、区域都有关系；公交车的收入处于固定的状态，而出租车的收入都会根据实际情况作出调整。 |
|   支出   | 车辆的支付有维修费用和加油费用；维修费用和车辆的使用时长有很大关系，而加油费用则和是否频繁用车有很大关系。 |
|   余额   | 汽车用量都很频繁，需要耗油，需要搭载乘客，支出很多，而收入很少，所以留下的余额很低，需要谨慎驾驶才能节省出称心的余额来。 |
|   备注   | 如果汽车停在某个非常繁忙的区域需要按照时间状况和空间状况来停车；在空间方面，避免不可及的停车；在时间方面，操心留意停车时间，如果超时停车很可能要交停车费。 |

天堂应该就是图书馆的模样，首先需要储备和计算机编程、阅读与推广密切相关的知识；不忘初心，继续了解与Apache密切相关的内容；坚定地做一名行路人，双手拿着车流预测模型的研究结果，甚至要对车订单、机场飞机订单进行探索性分析。

总之，从城乡车流量的变化情况来看，相信三大城市都可以有一个光明的发展前景。

## 九、分析

> 海角天涯，天南地北。天在、地在、人依在，仍记当时人。哪是物是人非？村路仍未认全，地非微改认命，又如何走遍寰宇？更何谈昔日故人？四合院闭户，广场地留人。鸭拨双掌，鱼游湖边，鸽飞树丛，猪哼、羊咩、狗叫此起彼伏，机车之声更盖过言语之人。闲来无事飘过，喇叭卖菜如常，人流汇聚，你我皆可，呼声一句，买卖一条街下！

### ㈠汽车车流的分析

![汽车出行](https://img.picgo.net/2024/03/30/1ce0a9d4bec6b6fc2d430c252eccaff91ea371b31016970e.png)

#### ⑴具体流程

1. **统计行程**：既可以使用导航系统、也可以使用车载诊断系统，还可以手动记录。
2. **特征转换**：可以处理订单信息提到的数值型特征，需要根据缺失值、异常值和分布特征进行相应的转换与处理。
3. **统计结果**：依据特定路段以及车辆类型进行统计，关注某个路段的车流量变化趋势，要进行长期观察和数据分析。

#### ⑵情况分析

##### ㊀波动情况

**从汽车车流的波动情况来看**：运用车流波动原理，可以把车流密度的疏密变化比拟为水波的起伏，并抽象为车流波，从宏观角度描述了车流拥挤过程和消散过程；现实生活既有忙于去公司上班的汽车，又有去景点旅游的汽车，还有去医院看病的汽车，更有去市场购物的汽车；各种情况均有涉及，一星期之内的变化并不明显，都处于一个稳定的变化状态。

##### ㊁两车对比

**普通汽车与公交汽车的比对**：普通汽车为私家车，而公交汽车为公共汽车；前者承载的人数较少，而后者承载的人数较多；前者可以根据自己的意愿选择出行路线，而后者则有固定的行驶路线；前者大街小巷，无论哪个公路路口都很容易见到，家用汽车很容易在周围遇到合适的加油站，不用担心汽车中途行驶问题；后者在公路上很容易见到；在公路上很容易看见公交车，尽管搭载者很多人，但是公路上公交车车流量变化仍处于一个稳定的状态。

##### ㊂自我操作

**司机乘客各司其职各就其位**：司机驾驶之时需要考虑到交通规则、驾驶习惯、车辆维护等因素，需要根据道路状况、交通信号、车辆状态对车辆进行安全有效的控制驾驶汽车的时候要考虑到周围汽车的利益，驾驶飞机的时候要考虑到周围飞机的利益；汽车车流的变化情况才没有很大的波动情况，汽车车流都适应于当下的环境，处于一个稳定的状态。

### ㈡飞机流量的分析

![飞机飞行](https://img.picgo.net/2024/03/30/6062e184681d6ff07c966d60f4dbd61f19c332f91acfc1fa.png)

#### ⑴统计

依据时间变化规律，统计与天、星期、月、年这四个周期相关联的数据，将与飞机流量的变化情况进行统计、整理与分析。
在一天之内、一星期之内、一月之内、一年之内，飞机流量的分布情况处于平衡状态；在工作时刻，飞机流量处于上升趋势；在休息时刻，飞机车流处于下降状态；飞机流量既有高峰期，也有低谷期；飞机从合适的时间出发，一直持续到需要的时刻，整体过程处于发展的稳定时期。

#### ⑵比较

将白天和夜晚每个时刻的飞机流量进行对比可以发现：

1. 飞机车流在●夜晚时刻处于适当状态，既有上升，也稍有下降，处于稳定状态。
2. 飞机车流在○白天时刻处于合适状态，星星点点，集中在下午，处于发展状态。

#### ⑶总结

飞机车流整体一直处于稀疏的状态，并没有汽车车流密集，一般集中在下午时刻，航班较少受到自然天气的影响，航线并不繁忙。

## 十、环境

|    分类    |                       内容                       |
| :--------: | :----------------------------------------------: |
|  设备名称  |                  LATOP-VCCAL4LA                  |
|   处理器   | Intel(R) Core(TM) i7-8565U CPU @ 1.80GHz 1.99GHz |
|  机带RAM   |                8.00 GB(7.85可用)                 |
|   设备ID   |       6C960FFD-1E6E-4777-A12B-DDB03A0BF764       |
|   产品ID   |             00342-35437-66644-AAOEM              |
| 系统和触控 |           64操作系统(基于x64的处理器)            |
|  笔和触控  |         没有可用于此显示器的笔或触控输入         |

## 十一、要点

### ㈠安装测试

1. **进行准备工作**：确定测试目标、确定测试范围、准备测试环境、备份重要数据、关闭无用程序、关闭无用服务、确定测试顺序、确定测试策略、建立跟踪机制。
2. **检查磁盘空间**：总体容量、已用空间、可用空间。
3. **检查端口情况**：使用命令提示符、使用资源监视器、使用合适命令。
4. **个人小组搭建**：明确目标、明确任务、选择成员、制定规则、制定责任、小组文化、定期回顾、定期总结。

### ㈡基本步骤

| 具体内容 | 四字详解 | 四字详解 | 四字详解 | 四字详解 | 四字详解 | 四字详解 |
| :------: | :------: | -------- | -------- | -------- | -------- | :------: |
| 安装类型 | 类型分类 | 类型统计 | 全新安装 | 典型安装 | 安全安装 | 便捷安装 |
| 安装目录 | 磁盘空间 | 安全问题 | 权限问题 | 特殊目录 | 主要目录 | 次要目录 |
| 安装产品 | 大量统计 | 认真研究 | 仔细执行 | 准确工作 | 检查性能 | 测试验证 |
| 启动安装 | 处理环境 | 准备工作 | 启动设备 | 开始安装 | 安装过程 | 完成安装 |
| 自动启动 | 没有干预 | 自动运作 | 自动执行 | 节约资源 | 减少占用 | 减少隐患 |
| 手动启动 | 人工操作 | 干预启动 | 主动打开 | 主动运行 | 直接参与 | 直接操作 |
| 检验过程 | 提高效率 | 降低成本 | 减少风险 | 不断对比 | 不断验证 | 不断检验 |
| 安装完成 | 明确分类 | 软件硬件 | 配置完成 | 部署完成 | 使用功能 | 使用服务 |
| 停止安装 | 研究系统 | 研究问题 | 分析错误 | 分析冲突 | 手动删除 | 手动卸载 |

### ㈢测试要求

1. 对各个界面的跳转功能进行测试，选择某一行信息，将代码作为参数，传递到图形分析界面中，并根据历史数据绘制出相关图形。
2. 在翻译完成Z之后，将程序放到英语等其它操作界面中进行测试，检测一下会不会出现乱码等问题。

### ㈣测试原则 

1. 遵守尽早测试和不断测试这两个原则。
2. 测试的时间应尽可能进行宽松的安排，不要寄希望于用最短的时间完成一个高水准的测试。
3. 考虑到输入的合法性与不合法性。
4. 考虑到各种边界条件。

### ㈤测试方法

1. **单元测试**：关注测试对象、关注测试粒度、关注独立性、关注自动化，进行早期测试、进行白盒测试。
2. **集成测试**：关注测试对象、关注测试方法、关注测试策略、关注测试工具、关注缺陷管理。
3. **系统测试**：黑箱测试、数据测试、穷举测试、操作测试、模型测试。
4. **验收测试**：确认需求、分析需求、制定计划、执行计划、评估结果。
5. **动态测**试：关注功能错误、关注性能问题、关注安全漏洞。
6. **静态测试**：不需要运行程序、发挥人的思维优势、对测试人员要求较高、运行成本低、运行容易实现。

## 十二、测试

### ㈠测试定位

| 测试人员 | 具体任务分配 | 具体任务分配 | 具体任务分配 | 具体任务分配 | 具体任务分配 | 具体任务分配 | 具体任务分配 | 具体任务分配 | 具体任务分配 |
| -------- | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| 测试组长 | 负责测试组织 | 负责测试管理 | 负责测试协调 | 编写测试计划 | 编写测试方案 | 设计测试实例 | 确认测试环境 | 编写测试报告 | 组织测试评审 |
| 测试成员 | 进行环境搭建 | 测试环境状态 | 进行环境检验 | 编写测试实例 | 执行测试操作 | 参与测试评审 | 运行测试结果 | 报告测试缺陷 | 进行测试跟踪 |

### ㈡测试内容

1. 分析磁盘空间的使用情况、分析端口之间是否存在冲突，分析个人小组的配置情况。
2. 通过加载文件，查看是否能够实现国际化翻译，翻译的内容是否符合预期要求，是否存在部分内容未翻译的情况。
3. 通过加载预先编辑好的文件，来实现状态切换的功能，查看各界面、各对话框、各控件等内容是否完成状态切换，是否与预期要求相符。
4. 对放大及缩小功能进行测试，查看是否能够通过点击数据跳转到指定图形分析界面。
5. 对各个界面的功能按钮进行点击测试，查看是否存在程序崩溃的情况。
6. 本次测试的主要目的有两个，一个是保证产品能够安装并运行；另一个是对测试进度中提到的具体模块进行测试。
7. 了解程序在运行过程中存在的问题，分析问题产生的原因，总结解决问题的规律，去更好地完善程序。
8. 测试可以分为功能测试和非功能测试两大类。功能测试包括：安装、功能检测、接口测试、卸载测试、协议测试；非功能测试包括：兼容性、可靠性、安全性以及专项测试。

### ㈢测试要求

| 测试目的 | 具体内容     | 具体内容     | 具体内容     | 具体内容     | 具体内容     | 具体内容     | 具体内容     |
| -------- | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| 提高质量 | 明确测试目标 | 明确测试范围 | 指定测试计划 | 设计测试用例 | 引入自动测试 | 加强团队沟通 | 持续进行测试 |
| 减少错误 | 指定详细计划 | 设计高效实例 | 进行测试准备 | 进行持续集成 | 提高测试精度 | 反思测试疏漏 | 建立反馈机制 |
| 增强质量 | 明确质量标准 | 优化测试流程 | 引入管理体系 | 进行人员培训 | 加强质量检查 | 总结质量问题 | 进行测试创新 |
| 提高稳定 | 优化测试环境 | 实施自动测试 | 加强错误处理 | 加强异常捕获 | 检查测试情况 | 改进测试问题 | 进行测试监控 |
| 错误反思 | 澄清问题定义 | 深入分析错误 | 收集错误信息 | 寻找错误根源 | 独立解决问题 | 寻求外部帮助 | 总结经验教训 |

### ㈣测试进度

| 阶段分类 | 如何测试 |
| :------: | :------: |
| 第一阶段 | 安装流程 |
| 第二阶段 | 图形绘制 |
| 第三阶段 | 状态切换 |
| 第四阶段 | 国际翻译 |
| 第五阶段 | 产品整合 |

## 十三、问题

### ㈠障碍问题

1. 在柱状图和韦恩图的绘制过程中出现了浮点型变量计算结果不准确的情况。
2. 出现鼠标移动缓慢、桌面卡顿的情况。
3. 在通过样式表来给主界面添加背景图片时，出现添加失败的情况。
4. 在不断放大及不断缩小过程中，因越界问题，程序可能会出现崩溃的情况。
5. 在无限度放大的情况下，可能会出现绘图不清晰的问题。
6. 在进行国际化翻译的过程中，界面中的字段可以直接翻译成对应的语言，但是某些字段无法直接翻译。
7. 在实际应用过程中出现了因字段中多加一个字母而无法将数据插入到数据库的情况。
8. 程序在进行最大化操作时，主界面菜单栏中留有很大的空白部分。

### ㈡解决方法

1. Decimal Number 格式基于十进制进行内部表达，可以将实数的绝对值转换为 Decimal Number 格式，此格式不会有精度丢失的问题，它的计算需要通过发送消息来进行计算。
2. 改变不合理的界面布局，一个界面不要同时运行多个窗口，那样容易造成卡顿的情况，及时关闭；
3. 整理完成后，及时进行本地存储，及时进行网盘备份。

### ㈢经验教训

增强逻辑思维能力，既要考虑到性能，也要考虑到负载；从简单的宣传介绍开始做起，无惧实际操作中遇到的各种问题；了解原理，运用到实践之中。

## 十四、评价

> 妥善保存测试计划、测试用例、出错统计、分析报告等内容；程序被修改后，测试人员应该重新进行测试，以确保在修改过程中没有产生新的错误；谨慎进行合理的输入，警惕不合理的输入；提高测试的精确度，避免测试的随意性。

### 测试准则

1. **完整性准则**：应当覆盖所有功能、应当覆盖所有特性、应当覆盖所有运行环境、应当覆盖各个角落；
2. **独立性准则**：测试过程应当独立于开发过程，应当避免利益冲突，应当避免潜在的偏见。
3. **有效性准则**：针对潜在的风险点进行深入测试和深入验证，改进测试方法，改进测试技术。
4. **可重复准则**：重复运行相同的测试用例应当得到相同的结果，确保测试结果的稳定性和可靠性。
5. **及时性准则**：在早期阶段进行，以便于尽早发现和解决问题，提高整体质量。
6. **可追溯准则**：每个测试用例都应当能够追踪到对应的需求或规格说明，确保工作和需求保持一致。
7. **文档化准则**：测试应当进行充分的文档记录，确保测试工作的透明度和可管理性。

## 十五、结果

自行车、电动车、火车、三轮车、卡车、汽车、飞机等交通工具在我们的生活中随机可见。

我深信Apache旗下的项目好比万丈高楼之地基、参天大树之树状、美丽花朵之枝条。通过这次报告了解到很多Apache旗下开源免费的项目；翻译并了解了Hadoop、Spark、HBase这三个非常流行的开源项目，身体力行地进行了安装与测试；以后肯定会继续了解其它开源项目,参与到开源项目的建设与发展中来，甚至有勇气想要让已经搁置在一旁的开源项目重新活跃起来；通过了解Apache旗下的各个项目，明确了将来想要深入研究各个项目的目标。

以鱼骨图的形式绘制了城乡车流量的执行计划；以思维导图的形式绘制了城乡车流量的执行流程；以韦恩图的形式绘制了城乡车流量的变化情况；以柱状图的形式绘制了城乡车流量的发展状况；依据随机森林模型和线性回归模型这两大模型，结合冒泡排序、选择排序、插入排序、快速排序这四大排序算法，通过对邯郸、石家庄、天津这三大区域车流量的发展状态进行对比，可以对城乡车流量的变化情况进行回顾、在线与展望。

开源项目的建设肯定与运行环境、编程语言密切相关。运行环境的配置处于较好的状态，然而缺少对于编程语言的熟悉感，因此在四大算法的可视化方面出现了一些障碍，尽管如此，在一步步的摸索之中，也逐渐了解并熟悉了四大算法的思想。

对于数据的作用和测试的作用进行了更加深入的探讨，可以更进一步地了解问题并解决问题。

## 十六、结论

在算法思想和编程语言方面，首先了解的是前者，然后才了解到了后者；随机森林和线性回归两大思想要进行更加深入的探究和整理，以求更进一步地理解城乡车流量的变化情况；对于Java和Python两大编程语言的了解不能一蹴而就，要不断深入探讨、不断分析。

代码运行占据了很大的篇幅；Java代码逐渐深入，而Python代码则层层递进；亲身敲打了四大算法的Java代码实现和Python代码实现，了解了两大编程语言的运行逻辑；参考Java代码的思想，依据手写验证，进行了四大算法可视化；我对于四大算法很深刻的印象有交换、移动、向上、向下、向前、向后、向左、向右。

城乡车流量必定会有高峰期和低谷期。无论是在高峰期，还是在低谷期，都要心平气和、稳定心态；在高峰期之内，要鼓足干劲，从从狭小的空间内挤出自己的空间来，同时要顾及到周围人和车的利益，行驶的时候应当如此操作，更何况停车的时候呢？在低谷期要以平静的心态从既定的目标迈向自己选择的目的地；在驾驶结束之后，为车辆寻找一个合适的庇护港湾。

继续绘制更多与城乡车流量紧密相关的流程图和思维导图，以辅助城乡车流量的发展；继续写作更多与城乡车流量紧密相关的文案，以了解城乡车流量的状态；继续敲打与城乡车流量紧密相关的代码，以稳定城乡车流量的发展；继续学习更多与城乡车流量紧密相关的思想，以便于为城乡车流量的发展贡献绵薄之力。

## 十七、其它

![单车](https://img.picgo.net/2024/03/30/c53159f040cc8d4e355ef5d3724724a6d88c3b24d3f56969.png)

### ㈠目的

熟悉与时间相关联的函数；了解与时间相关的概念，进行与时间转换相关联的操作；在恰当的时间，用恰当的工具转换出精确的数据；熟练地操作与时间转换有关的编程语句和软件。

### ㈡特征

飞机车流分析需要使用与时间相关联的函数：比如 NOW函数、MONTH 函数、YEAR函数等；还需要了解与时间相关联的概念，比如时间的五个特征：相对性、绝对性、一维性、同时性、均匀性；每个时间特征都可以总结出来与时间相关联的概念，比如时间、运动、物质、参考系、联系等。

### ㈢比较

与汽车车流分析相比，我觉得飞机流量最大的特点就是距离我们比较遥远，平常很难有接触的机会，这次可以使用相关算法和思想对机场流量进行分析，就是一个很大的幸运；希望分析研究以后的结果可以为Apache基金会的发展作出更大的贡献，同时也希望这次对机场流量的分析也可以为中国飞机场事业的发展做出自己的独特贡献。

### ㈣总述

城乡车流量都处于稳定状态；城乡车流量在每日之内、每周之内、每月之内、每年之内都控制在一定范围之内；在特殊时期，有时会稍有波动，然变化趋势稳定。

## 十八、建议

![火车](https://img.picgo.net/2024/03/30/e0f30f94cf4bd6ab0587df979410d70fdd8236bead06e40a.png)

立宏图大志，从小事做起。既可危楼高百尺、手可摘星辰，又可路遥知马力、日久见人心。

我认为如果要进行与城乡车流量发展相关的分析，首先需要找好个人独特的定位，从低处着眼，做到谨言慎行四个字。

提前声明，运用好身边的工具，必要时让所有朋友都可以有机会接触并参与到城乡车流量的学习与实践之中。

学习本身就是一个由熟悉到熟练的过程。结合已学的与城乡车流量密切相关的知识，及时做好整理、更新和备份；熟能生巧，只有将基础知识应用到相关实践之中，才能锻炼出真正的本领。

# 结语

```java
public class practice
{
	public static void main (String[] args)
	{
		System.out.println("hello")
	}
}
```

```python
print("Hello World！")
```

人生的道路虽然漫长,但紧要处常常只有几步,特别是当人年轻的时候。

此篇所写的心得体会来源于进入石家庄学院理学院数据科学与大数据专业时的所见所闻和所学所得；在阅读和编程这两个方面受益匪浅。

写此项目主要是为了可以辅助生活和学习，为学校生活和家庭生活提供帮助，另一方面也可以增加自己适应环境的机会，提高自己面对困难和解决问题的能力。

使用 Apache旗下的项目进行数据读取和预处理相对于其他处理方式而言，既保持了大数据处理的高效性，又保证了代码编程的简洁性。

简单确实优于复杂，然而需要经历一个不堪回首的过程，回忆痛苦不堪的往事；尽管如此，这让我们更专注于精彩的过程，而不再计较于开始和结果；然而不计环境气氛，付出虽然有收获，也得向现实妥协，与周围平衡。
如果可以来到图书馆分析与大数据相关的内容，我向前看了看，无非两个字：整理；向后看了看，也无非两个字：打印。笔法太重，落笔太轻，仅以个人的看法来研究与城乡车流量相关的大数据知识。
阅读编程相关国内知识，好好地去实践所学所得。

主要是接受过学校教育，另外也参加过学校组织过的实习活动，从中也学到了很多生活经验和学习知识，通过知识的学习和帮助，在现实生活中结实了很多朋友，增长了很多面对挫折和困难的能力。

实习之中会有一些自己可以去做，而且很有必要去做的事情。在和这些朋友的交流之中，不仅仅增加了面对社会挑战的机会，并且有了更多与周围朋友交流的机会。

在生活中渐渐懂得首先确实应该好好地照顾好自己，然后再去应对考试和面试。

收获就是巩固了基础知识，制作了一些相关图片，有真情实感，有成就感。

并非结局,未完待续，有待来者！

# 文献

> 三篇词作由自己创作，文心一言分别根据三首词创作出了三首诗，而微信读书中的内容则是完成这篇设计之后将要参考的内容。

1. 文心一言中与依依的部分对话：https://yiyanapp.baidu.com/talk/share?shareId=EWdqrEQ1eR88C&UK=MkKFL9OY2c_O3Zh5_w-odw&vp=0&sk=775608d6
2. 文心一言中与费翔的部分对话：https://yiyanapp.baidu.com/talk/share?shareId=EWdqrEQ1eR8dC&UK=MkKFL9OY2c_O3Zh5_w-odw&vp=0&sk=1facbff6
3. 《C++从入门到精通》：https://weread.qq.com/web/bookDetail/8dd32690813ab78f5g018f82
4. 《Java从入门到精通》：https://weread.qq.com/web/bookDetail/ccc32d80813ab6bfbg0182ea
5. 《Java编程的逻辑》：https://weread.qq.com/web/bookDetail/b51320f05e159eb51b29226
6. 《Java并发编程之美》：https://weread.qq.com/web/bookDetail/81c32b507184869281c2a23
7. 《Python从入门到精通》：https://weread.qq.com/web/bookDetail/f7a320007198d668f7ae296
8. 《Python编程：从入门到实践》：https://weread.qq.com/web/bookDetail/19532980715c01921954a54
9. 《零基础学MySQL数据库管理》：https://weread.qq.com/web/bookDetail/56a32500813ab83fag018d4f
10. 《NoSQL数据库原理》：https://weread.qq.com/web/bookDetail/86832cf0720551d486809c8
11. 《Java Web从入门到精通》：https://weread.qq.com/web/bookDetail/593320b071e524f05931fc1
12. 《Linux命令行大全》：https://weread.qq.com/web/bookDetail/f5c32ac072287278f5cc0e6
13. 《Hadoop应用开发基础》：https://weread.qq.com/web/bookDetail/37d32f70718b735837d31f3
14. 《Hadoop HDFS深度剖析与实践》：https://weread.qq.com/web/bookDetail/4b932650813ab80dag016370
15. 《Hadoop 3实战指南》：https://weread.qq.com/web/bookDetail/bc332b80724b5d9ebc31844
16. 《Hadoop构建数据仓库实践》：https://weread.qq.com/web/bookDetail/bc332b80724b5d9ebc31844
17. 《Hadoop集群程序设计与开发》：https://weread.qq.com/web/bookDetail/fbf3275072037f1afbfd83
18. 《Spark编程基础：Scala版》：https://weread.qq.com/web/bookDetail/d6532da0718b748fd65216f
19. 《Spark编程基础》：https://weread.qq.com/web/bookDetail/4933297072027cf0493ac1f
20. 《循序渐进学Spark》：https://weread.qq.com/web/bookDetail/c47328605d0ebec471db5b5
21. 《Spark大数据实时计算：基于Scala开发实战》：https://weread.qq.com/web/bookDetail/85c32d20813ab77d0g011c19
22. 《Spark大数据分析实战》：https://weread.qq.com/web/bookDetail/9ff32e305c4d019ffe6f68d
23. 《Spark 3.0大数据分析与挖掘：基于机器学习》：https://weread.qq.com/web/bookDetail/2f332500813ab7186g01073d
24. 《Spark内核设计的艺术：架构设计与实现》：https://weread.qq.com/web/bookDetail/0c832fb05e12e40c8ca6190
25. 《Spark海量数据处理：技术详解与平台实战》：https://weread.qq.com/web/bookDetail/483326b071a52591483e940
26. 《大数据技术基础》：https://weread.qq.com/web/bookDetail/ca232c20717d32bfca2f70c
27. 《机器学习》：https://weread.qq.com/web/bookDetail/4f1323a0813ab830bg015271
28. 《云计算原理与实践》：https://weread.qq.com/web/bookDetail/4f6323a0717d31154f65d83
29. 《大数据分析与挖掘》：https://weread.qq.com/web/bookDetail/e083242072037f1ce08fe70

# 附录

## 一、测试类别

1. **单元测试**：针对编写的源代码，采用白盒测试技术；测试方法为：语句覆盖，判定覆盖，条件覆盖，条件组合。
2. **集成测试**：模块与模块的拼接，重点测试接口，多采用黑盒测试技术；测试方法为：自顶向下测试和自底向上测试。
3. **系统测试**：验证整个系统是否满足需求规格，软件系统的正确性是否满足需求规格，软件系统的性能是否满足需求规格，和外接设备的连接是否满足需求规格，采用黑盒测试技术。
4. **验收测试**：确保软件准备就绪，展示软件系统能否满足用户的需求，采用黑盒测试技术。
5. **静态测试**：静态测试的主要特征是不实际运行被测试的软件，对软件的编程风格进行评估，对软件的编程结构进行评估。
6. **动态测试**：动态测试与静态测试正好相反，必须真正地运行被测试的程序；通过输入测试用例，对运行过程中的输入数据和输出数据进行分析，从而得出测试结论。
7. **白盒测试**：把盒子打开，研究里面的源代码，研究程序执行的结果。
8. **黑盒测试**：不关心被测软件的内部结构，既关心软件的输入数据，也关心软件的输出结果。
9. **单点登录**：在多个应用系统中，用户只需要登录一次就可以访问所有相互信任的应用系统。

## 二、操作情况

| 操作步骤                                                     | 预期                                                   | 实际情况     |
| ------------------------------------------------------------ | ------------------------------------------------------ | ------------ |
| 双击安装向导                                                 | 打开并进入欢迎界面                                     | 预期效果一致 |
| 点击取消                                                     | 提示框弹出，点是退出，点否退出                         | 达到预期效果 |
| 点击下一步                                                   | 界面跳转，选取安装目录                                 | 实现预期效果 |
| 再次点击下一步                                               | 界面跳转，选择是否在桌面及开始菜单创建图标             | 预期效果完成 |
| 点击返回                                                     | 返回上一界面                                           | 预期效果成立 |
| 接着点击下一步                                               | 界面跳转，准备安装                                     | 预期效果符合 |
| 点击安装                                                     | 开始安装                                               | 预期效果实现 |
| 运行软件并点击完成                                           | 安装向导退出，程序运行                                 | 预期效果一样 |
| 点击语言菜单下中文繁体或中文简体或英文动作                   | 所有用户可见字符串，均被翻译为中文繁体或中文简体或英文 | 预期效果相同 |
| 皮肤菜单下，默认风格或富途纯蓝或时尚暗黑或淡雅银灰或午夜紫兰动作 | 各个界面中所有控件转换为对应的样式                     | 预期效果重合 |
| 图形菜单下先大后小或图形分析或先长后短动作                   | 切换至对应各个界面，并绘制相应图形                     | 相同预期效果 |
| 双击屏幕空白处                                               | 图形出现                                               | 预期效果成功 |
| 点击向上键                                                   | 图形放大                                               | 预期效果同样 |
| 点击向下键                                                   | 图形缩小                                               | 预期效果冲锋 |
| 点击向左键                                                   | 图形左移，随着十字线的左移而左移                       | 预期效果相遇 |
| 点击向右键                                                   | 图形右移，随着十字线的右移而右移                       | 预期效果出现 |
| 移动鼠标                                                     | 十字线随鼠标的移动而平滑移动，无卡顿                   | 预期效果现身 |
| 点击浏览菜单图表动作                                         | 界面跳转，并显示退保                                   | 出来预期效果 |
| 双击表格任一行数据                                           | 根据要求跳转至图形分析菜单下的某一界面                 | 预期效果相知 |
| 跑马灯前面感叹号                                             | 跑马灯关闭                                             | 预期效果相识 |
| 点击尚未打开过的界面                                         | 界面跳转不出现崩溃情况                                 | 预期效果到来 |
| 双击登录程序                                                 | 登录界面弹出                                           | 同样预期效果 |
| 点击登录按钮                                                 | 登录成功，并进入激活界面                               | 预期效果一样 |
| 单击启动按钮                                                 | 成功将用户信息写入                                     | 预期效果成功 |

# 致谢

> 太行山深处，千里送京娘；武安深山处，七步沟脚下；中间行路，烈日狰狞，青山妩媚，娟娟溪水；两侧车影稀疏，中间人影蹿动，其上数层瀑布；杨柳青青随风舞动，与水之流动相平。

![石家庄学院4年学习的总结和应用](https://img.picgo.net/2024/03/30/4e351f0baafe26b8c.png)

门前立柱，高山石刻，苍海飞燕，诚然如是，一见钟情！
如果让我选择一个职业场所，必定是图书馆的模样；如果让我选择一个大学，肯定是石家庄学院；如果让我再考虑一所大学的话，肯定是河北工业大学；如果再往上考虑的话，我愿意选择北京大学亦或是清华大学。
石家庄学院的信自然不必去写，因为那是我曾经热爱过、生活过的土地和岁月；河北工业大学的信，我觉得有必要去写，因为那是即将毕业的我选定的目标；至于最后的目标北京大学亦或是清华大学的信一定要写，因为它是中国的代表。

在学习编程的时候，自己独立地安装了解释器和编译器，并且能够根据不同阶段对编程的辅助工具进行进一步的更新和备份；加入了很多编程交流社区，与朋友们一起认识和研究了诸多实用的编程语言；参加了诸多程序设计比赛，将自己对于某段代码或语句的理解以程序搭配的形式表现了出来，效率重用、运行良好、层次清晰、条理清楚、状态稳定、结构紧密。

在摸索的过程中，接触了很多编程界大佬，有的来自于国内，而有的来自于国外；所使用的大部分内容都是国内常用的软件和网页，在语雀和Github搭建了个人定将长期使用的个人主页，还接触到了开源软件市场上很多优秀的软件；一个人能取得怎样的成就最要紧的是看自己，也看周围的环境氛围，然后需要有灵感一线的时刻！
它们就像一幅幅精心绘制的图画,有的灵感来自于天上，而有的灵感来自于地下；在其中学习了很多与大数据相关的技术，比如两大编程语言Java和Python、慢慢走出来的大象Hadoop、灵光一现的 Spark，对我影响最深的就是 Spark 了，因为了它沟通了所有的中国人的情感和所有的外国人的情感，当然少不了风雨探路人在其中了！目前最要紧的是记录，整理的过程还得经历一个漫长的备考期。
认识和了解了很多软件的开发者，开阔了编程的视野，提高了自己应对项目开发的能力；时光总是匆匆而逝；时光总是钟情于一步一个脚印慢慢行走的人，时光也同样钟情于一步一个台阶慢慢爬行的人；如果非得给自己的说和做加一个前缀来修饰的话，那肯定就是好好地；更进一步去说的话，目前来说，肯定就是好好地学习编程知识、好好地实践编程所得；之后肯定是好好地做每个有真情实感的中国人该做的事。
因此我相信：生活更美好，原来就是你，人生路漫漫，天涯未可期。
我们谁也不要妄图去改变时间，自己可以写下最好的个人计划书。
感谢数据科学与大数据技术 1 班的老师和同学们！
感谢石家庄学院图书馆和图书馆读者协会！                                                                                                                                     
