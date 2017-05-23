# 沿途风景

## 高中生涯
  * 高三组数学竞赛，省二等奖，[具体名单](https://zhoukekestar.github.io/assets/2011_math.html)

## 大学生涯（2011-09 ~ 2015-06）
  * `2011-09 ~ 2013-05` ACM
    * ACM训练，个人的[题目列表](http://acm.tzc.edu.cn/acmhome/userDetail.do?userName=zhoukeke)
    * ACM竞赛，[浙江省赛银奖](http://acm.tzc.edu.cn/acmhome/heroList.do?method=showTeamList&year=2013)
  * `2013-06 ~ 2013-09` [Farm](https://github.com/zhoukekestar/college-legacy).

    Tags: `ASP`, `C#`, `SQL-Server`<br>
    项目描述：老师外接的一个项目，通过收集农场温湿度，实时监控并可人为控制各种农场设备，以达到远程管理农场的目的。由2个计算机应用的同学，
    2个物理与电子信息科学的同学（负责设计电路，使用ZigBee搭建内网，收集温湿度等数据，通过2G/3G网络上传至服务器）共同完成。

    职责：项目软件Web客户端和后台通讯负责人

    结果：采用C#做为后台服务器，SQL-Server为数据持久层，使用ASP实时展现温湿度数据，并下发控制指令（如：打开风机使温度降低）。基本实现农场各项数据的实时监控，并能够下达指令，控制各种设备达到远程管理的效果。通过项目的参与，完整地了解整个的项目的流程，学校的理论知识也得到了实践。
    
  * `2013-09 ~ 2014-02` [mobile-life](https://github.com/zhoukekestar/MobileLife).

    Tags: `C`, `Linux`, `JAVA`

    项目描述：竞赛的课题，通过下发红外指令，控制一些可由遥控器控制的家电（车库，空调，电视等）。实践理论假设，并发表一篇论文。

    职责：带领小组成员通过开发嵌入式系统的软件和JSP控制页面，实现预定目标。
    
    结果：一篇公开发表的论文:[远程控制家具的软件设计](http://d.wanfangdata.com.cn/Periodical/hljkjxx201511146)。项目进行过程中，需要查阅大量linux和嵌入式的资料，自学能力得到较大提升。对Linux和C有了更深入的了解，其中也了解到了pipe、thread等概念。

  * 大学的课程项目
    * [A simple Chat](https://github.com/zhoukekestar/college-legacy).

      Tags: `Java`, `Socket`, `Java Swing`

      能够点对点通讯的桌面应用。Java课程的期末作品（由于对GUI和网络比较感兴趣）。其中深刻体会到swing布局和web布局的差异（HTML和CSS真是强大）。

    * [gobang](https://github.com/zhoukekestar/college-legacy).

      Tags: `C#`, `Socket`

      网络对战五子棋。C#课程的期末作品（出于对网络通信和GUI的兴趣）。

    * [magic-cube](https://github.com/zhoukekestar/college-legacy).

      Tags: `C++`, `OpenGL`

      电子魔方，OpenGL课程的期末作品。

  * `2014-02 ~ 2015-06` 大三下半学期和大四一整年（由于老师要求期末科目能过就行），在蓝麦电商公司得到了一份`full-time job`.
    由于学校的教学内容和公司的技术要求不匹配，自学当时主流Java框架，由于注重轻量化，所以会以mybatis和servlet为主。学习过程中，记录并开源了[SSH-start](https://github.com/zhoukekestar/SSH-Start)项目, 主要以做笔记为主，也是最早的开源尝试。也写过入门教程[Hibernate 4 简单入门样例](https://wenku.baidu.com/view/bfc233a9700abb68a882fb13.html), 类似的入门教程在[百度文库](https://wenku.baidu.com/u/STERERLEL)上也比较多。

## 2014-03 ~ 2015-06
岗位：Java开发工程师
工作内容：
* 公司基础技术服务的搭建，如：服务器的Linux安装，SVN，FTP搭建，Web Server（apache，nginx，tomcat）的搭建。
* 负责公司的后台的接口设计、实现和部署（包括公司和阿里云服务器）。提出采用RESTful风格的接口规范，以及整体迁移阿里云的建议，并得到采纳。
* 负责实现后台安全模块、后台支付模块。对接第三方支付，如支付宝支付，银联支付，满足了当时公司的支付需求，使得公司快速实现现金流的运转。
* 使用servlet写服务，JSP写web页面。负责土冒后台管理、土冒移动端页面、微信活动。满足了公司初期的后台管理。及时快速地发布土冒移动版、微信优惠活动，使得公司影响力与日俱增。

期间开源的项目：[SSH-start](https://github.com/zhoukekestar/SSH-Start), [zkk-components](https://github.com/zhoukekestar/zkk-components), [modules-for-java](https://github.com/zhoukekestar/modules-for-java) Tags: `Java`, `JSP`, `Spring`, `Servlet`, `Mybatis`, `MySQL`.

## 2015-07 ~ 2015-12
岗位：前端工程师
* 提出前后端分离的解决方案，使得项目得到较大的优化。使得项目问题定位更准确，前端优化更为灵活。
* 采用nodejs编写前端，并用模块化方式（require.js）组织前端页面。使得项目和页面结构更为清晰。
* 实施组件化（特指封装一段HTML，JS，CSS）方案，参考[tmall和polymer](https://github.com/tmallfe/tmallfe.github.io/issues/34)，造了一个简单组件化轮子`modules/webcom`。这使得前端页面的代码重用率有较大提升，项目推进速度加快。

期间开源了[modules](https://github.com/zhoukekestar/modules)

## 2016-01 ~ 2016-12
岗位：前端工程师
* 提出采用git + Docker化部署方案，并在前端领域得到了技术总监的许可，先于后端在阿里云上进行docker部署。
  采用`git push + auto build + deploy image`的工作流，在测试环境实现了代码变更的自动部署，极大提高了部署效率。
* 提出使用Weex编写android和ios客户端

关于Docker，之前，阿里云有推出他自己的云引擎ACE，最先采用的部署方式的ACE，后来，渐渐因为nodejs版本更新不及时，
相应速度和稳定性方面的问题，渐渐转向docker。


关于weex，也是因为2015的12月参加了阿里的D2，首次接触到weex，提出3端一致（晚于react）给我较大的震撼，一直惦记着。
到2016年6月开源，一直关注，云栖大会上，拉上技术部的小伙伴一起参加了。期间，能够看到后台重点推docker，前端重点推weex。于是，我也写了一个android版的[weex-quick-start](https://github.com/zhoukekestar/weex-quick-start)进行技术调研。


期间开源的项目：[weex-quick-start](https://github.com/zhoukekestar/weex-quick-start)


## 2017-01 ~ now
岗位：前端工程师
* 提出后台接口使用GraphQL标准，并率先在运营后台的用户权限与认证模块得到有效的落地实施，取得不错的效果。
* 最大化接近标准的页面架构方式，目前倾向riot
  > Close to standards.
  > Small learning curve.
  > Small, but complete.

最大化接近标准，主要是近年来，web发展迅猛，光编译工具就有grunt，gulp，webpack，browserify等等，前端框架也是层出不穷，
其中包括但不限于angular, vue, react, polymer等，但个人觉得他们的出现是由于webcomponents的可实现性和兼容的存在的问题。但又因为解决这个问题而抛弃了太多了标准，所以，个人倾向于类似riot的这种小而美，接近标准，少一些私有接口，更重要的是标准带来的便利性。

期间开源的项目：[web-components](https://github.com/zhoukekestar/webcomponents), [form-json](https://github.com/zhoukekestar/form-json), [input-validator](https://github.com/zhoukekestar/input-validator)

## 技能点
熟悉：Nodejs, HTML, CSS, JS

了解：
  * Languages: JAVA, JSP, ASP, C#, C, C++,
  * DB & Cache: MySQL, MongoDB, Redis, SQL-Server
  * Libs: OpenGL, Java Swing
  * OppDevs: Linux, Bash, Docker

## 个人缺点
太会折腾
