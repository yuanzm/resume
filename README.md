个人简历
======================
袁梓民的个人简历

## 个人信息

**姓名**：袁梓民

**性别**：男

**学校专业**：**中山大学**软件学院

**blog**：http://www.cnblogs.com/yuanzm

## 技术能力

专注并且热爱web开发，熟练掌握JavaScript、HTMl、CSS以及JavaScript框架来搭建web应用。了解原生JavaScript和JavaScript类库的使用。

* 掌握的JavaScript类库：jQuery、Prototype
* 掌握的JavaScript框架：BackBone、Vuejs、Angular.js、React.js
* 掌握的CSS预编译器：LessCss、Sass
* 掌握JavaScript模块加载器：RequireJS、Browserify
* 掌握项目构建工具：Grunt、Gulp
* 掌握项目管理和协同工具的使用：SVN、Git
* 掌握前端测试框架以及工具：Jasmine、Mocha
* 掌握基本后端开发：NodeJS、Python
* 掌握web相关技术：MongoDB、CoffeeScript、SEO、Socket.io、Express、Tornado等

##个人经历

* 2012年进入中山大学学习
* 大一开始接触Web
* 大二开始疯狂投入web学习
* 大二下开始加入创业团队，系益米通服务有限公司的微信前端工程师
* 大二暑假在广州时代财富有限公司上班实习，参与建设银行网上银行前端原型开发

## 个人作品

### [米芝莲](http://www.wizland.cn/wizland/index/)
项目地址： http://www.wizland.cn/wizland/index/
- 简介
  + 米芝莲是一个在线食材选购网站，同时具有移动端和PC端。项目采取了SpringMVC框架，充分利用了框架所宣传的MVC、Restful风格、简洁高效等特性。
- 项目收获
  + 熟悉了Eclipse环境的开发，熟悉了Java Web应用的开发流程
  + 尝试了没有框架条件下的移动端Web开发
  + 对于前端模块化有了更加深层次的理解
  + 理解了组件化开发对于前端开发的重要性
- 项目总结
  + 在本项目中，我担任了移动端和PC端的前端开发一职。在这个项目中，充分认识到了前端架构的重要性。在同时具有移动端和PC端的非响应式应用中，怎么合理把握好前端结构显得尤为重要。既然要分成移动端和PC端，主要原因是页面排版不同，但是很多逻辑是通用的，因此怎么利用browserify等前端模块化工具来提高代码复用性成为一个很重要的任务。同时，本项目中还第一次尝试了设计，完成了移动端和PC端的大部分设计稿，认识到了作为一名前端工程师，设计能力的不可或缺性。总的来说，这个项目实战型很强，收获很大。

### [LiveChat](https://github.com/yuanzm/Live-Chat)
项目地址： https://github.com/yuanzm/Live-Chat

- 简介
  + Live-Chat应该是所做过的最复杂的一个Web应用。项目采用Node的Express框架作为后端架构，采用非关系型数据库MongoDB实现聊天记录持久化，采用socket.io实现具有高兼容性的实时消息传送。 
- 收获
  + 认识到项目架构的重要性
  + 总结出了自己的前端模块化工作流
  + 熟悉了Nodejs应用开发流程
- 总结
  + 作为聊天WebApp，决定了整个页面是富交互的，所以如果仅仅是单纯的模块化并不能保证良好的可扩展性。于是总结出了前端组件化开发的思想:前端应该根据应用的复杂程度将前端分成三道四层，第一层为数据操作层，封装了很多AjaxAPI，负责与后端进行数据交互；第二层为UI组件层，为了最大化提高页面组件的复用性，页面上的元素应该根据功能划分成很多模块，也即HTMl和CSS同样是模块化的；第三层为UI组件通信层，为了降低UI组件的耦合性，组件之间的通信应该是通过事件机制的，而不是直接互相调用另一个模块的内部函数。整个项目最大的难点是怎么降低不同组件之间的耦合性，不然在开发的过程中，一个模块牵扯到很多模块就会顾此失彼。

### [Home-Cloud]()
Home-Cloud是基于Python的Tornado框架构的一个移动端WebApp。Home-Cloud的开发并没有花费很长时间，得益于之前的Web开发经验。Tornado本身不是一个MVC框架，于是在组织后端代码的时候借鉴了Nodejs的Express框架，将整个后端代码架构成由model层、router层以及view层构成的的MVC结构。好处是显而易见的，当业务逻辑愈发复杂，这种分层架构能够保持项目代码丝毫不会紊乱。前端得益于Tornado的模板机制，在大部分模板引擎都具有继承等优点的情况下，多出了UI模块这一点，使得每一个模块可以拥有自己的html、CSS和js，能够很好符合Web组件化开发的特点。通过这个简单的项目，很好展现了近两年的Web开发经验，从刚开始的写一步看一步到今天的工程思想，感觉收获很大。


### [求组队](https://github.com/yuanzm/project-qiuzudui)
项目地址：https://github.com/yuanzm/project-qiuzudui

所做的第一个项目，项目致力于创建一个在校大学生竞赛组队平台，通过这个平台，用户可以在主页查看到近期学校的比赛并能够发出组队邀请。在这个团队里面，我与另外一名成员进行合作负责前端开发。作为第一个项目，主要问题是团队协作以及项目工程经验不足的问题。由于没有很好的组织好项目结构，以及版本控制意识的缺乏，导致后期代码结构混乱的问题频频出现。通过这个项目，领会了项目工程思维的重要性，以及团队协作的重要性。


### [益米通](https://github.com/yuanzm/emitong.git)
项目地址：https://github.com/yuanzm/emitong.git

第一次做手机端的Web应用，整个项目用于展示与益米通公司合作商家的优惠信息。项目遇到的主要问题是移动端Web经验缺乏，不同设备的适配问题等。通过查阅资料以及咨询前辈，在这个项目中掌握了Web响应式应用的开发，同时了解了微信公众平台应用开发的基本流程。

### [学院党委网站维护](http://pro.ss.sysu.edu.cn:8080/party_affairs/index.jsp)
项目地址：http://pro.ss.sysu.edu.cn:8080/party_affairs/index.jsp

主要任务是部署基于Java Web的网站服务器和网站的日常维护工作。

### [Snake](https://github.com/yuanzm/Snake)
项目地址：https://github.com/yuanzm/Snake

在闲暇的时候用JavaScript写了一个贪吃蛇小游戏


## 自我简介

从大一开始了解web技术，大二开始正式投入学习web各种技术。正处于快速增长技能的阶段，对于web有着极高的热情，每天坚持学习web。

目前为止对于前端技术比较了解，但是正在学习web后端技术，目标是成为一名优秀的web全端工程师。

拥有较强的学习能力和沟通能力，能够比较良好的和团队成员协同完成开发。
