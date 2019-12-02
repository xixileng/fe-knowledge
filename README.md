## 前端知识图谱

![前端知识图谱](./前端知识图谱.png)

### Todo List
* 为图谱对应的列表增添超链接，链接到知识点对应的更多内容的页面(建议文档渠道：官网、MDN、GitHub、wiki，中英文随意)
  - [x] 编程基础
  - [x] 开发软件
  - [x] 类库框架
  - [x] 知识进阶
  - [ ] 工程开发
  - [ ] 编程思想
  - [ ] 领域分支
  - [ ] 社区发展
  - [ ] 计算机基础
  - [ ] 后端知识
  - [ ] 软技能

* 增加二级图谱，进行更详细的拓展
  - [ ] 编程基础
  - [ ] 开发软件
  - [ ] 类库框架
  - [ ] 知识进阶
  - [ ] 工程开发
  - [ ] 编程思想
  - [ ] 领域分支
  - [ ] 社区发展
  - [ ] 计算机基础
  - [ ] 后端知识
  - [ ] 软技能


## 编程基础

### HTML(5)

- [元素](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element)
- [DOM](https://developer.mozilla.org/zh-CN/docs/Web/API/Document_Object_Model)
- [语义化](https://www.zhihu.com/question/20455165)

### CSS(3)

- [CSSOM](https://developer.mozilla.org/zh-CN/docs/Web/API/CSS_Object_Model)
- [选择器](https://developer.mozilla.org/zh-CN/docs/Web/Guide/CSS/Getting_started/Selectors)
- [布局](https://developer.mozilla.org/zh-CN/docs/Learn/CSS/CSS_layout)
- [交互](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_Animations/Using_CSS_animations)
- [绘制](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-tree-construction?hl=zh-CN)

### JavaScript(ES6+) 

- [类型](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Data_structures)
- [原型链](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)
- [作用域](https://developer.mozilla.org/zh-CN/docs/Glossary/Scope)
- [闭包](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Closures)
- [事件](https://developer.mozilla.org/zh-CN/docs/Web/Events)
- [异步](https://developer.mozilla.org/zh-CN/docs/learn/JavaScript/%E5%BC%82%E6%AD%A5)
- [正则表达式](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Guide/Regular_Expressions)

## 开发软件

### 编辑器和IDE

- [VIM](https://www.jianshu.com/p/bcbe916f97e1)
- [Sublime Text3](https://www.sublimetext.com/3)
- [Notepad++](https://notepad-plus-plus.org/downloads/)
- [WebStorm](https://www.jetbrains.com/webstorm/)
- [Visual Studio Code(强烈推荐)](https://code.visualstudio.com/)

### 调试工具

- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools)
- [Firebug](https://getfirebug.com/)
- [Postman](https://www.getpostman.com/)
- [Fiddler](https://www.telerik.com/fiddler)
- [Charles](https://www.charlesproxy.com/)

### 切图

- [Sketch](https://www.sketch.com/)
- [PhotoShop](https://www.adobe.com/cn/products/cs6/photoshop.html)
- [PxCook](https://www.fancynode.com.cn/pxcook)

## 类库框架

### 工具库

- [jQuery](https://jquery.com/)
- [Zepto](https://zeptojs.com/)
- [Bootstrap](https://getbootstrap.com/)
- [Prototype](http://api.prototypejs.org/)
- [Underscore](https://underscorejs.org/)
- [Lodash](https://lodash.com/)
- [RxJS](https://rxjs-dev.firebaseapp.com/)
- [moment](https://momentjs.com/)

### 开发库/框架

- [Vue](https://cn.vuejs.org/v2/guide/)

	- [Vuex](https://vuex.vuejs.org/zh/guide/)
	- [Vue-router](https://router.vuejs.org/zh/)
	- [Vue-cli](https://cli.vuejs.org/zh/guide/)
	- [Element UI](https://element.eleme.io/#/zh-CN)

- [React](https://zh-hans.reactjs.org/)

	- [Redux](https://redux.js.org/)
	- [React-router](https://reacttraining.com/react-router/web/guides/quick-start)
	- [create-react-app](https://github.com/facebook/create-react-app)
	- [Ant design](https://ant.design/index-cn)

- [Angular](https://angular.io/)
- [Ember](https://emberjs.com/)
- [Knockout](https://knockoutjs.com/)
- [Backbone](https://backbonejs.org/)

## 知识进阶

### 网络通信

- 通讯协议

	- [HTTP1.0/1.1](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Overview)/[2.0](https://developers.google.com/web/fundamentals/performance/http2?hl=zh-CN)/[3.0](https://blog.cloudflare.com/zh/http-3-from-root-to-tip-zh/)
	- [HTTPS](https://zh.wikipedia.org/wiki/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%AE%89%E5%85%A8%E5%8D%8F%E8%AE%AE)
  - [TCP](https://zh.wikipedia.org/wiki/%E4%BC%A0%E8%BE%93%E6%8E%A7%E5%88%B6%E5%8D%8F%E8%AE%AE)
  - [UDP](https://zh.wikipedia.org/zh-hans/%E7%94%A8%E6%88%B7%E6%95%B0%E6%8D%AE%E6%8A%A5%E5%8D%8F%E8%AE%AE)
  - [WebSocket](https://developer.mozilla.org/zh-CN/docs/Web/API/WebSocket)
  - 补：[HTTP1.0、HTTP1.1 和 HTTP2.0 的区别](https://juejin.im/entry/5981c5df518825359a2b9476)、[TCP和UDP的区别](https://zhuanlan.zhihu.com/p/24860273)

- API风格

	- [RESTFul](https://zh.wikipedia.org/wiki/%E8%A1%A8%E7%8E%B0%E5%B1%82%E7%8A%B6%E6%80%81%E8%BD%AC%E6%8D%A2)
	- [RPC](https://zh.wikipedia.org/wiki/%E9%81%A0%E7%A8%8B%E9%81%8E%E7%A8%8B%E8%AA%BF%E7%94%A8)
	- [GraphQL](https://graphql.cn/)

### 性能

- [性能指标](https://juejin.im/post/5b0260ba51882542682e8250)

	- 首次绘制（FP）
	- 首次内容绘制（FCP）
	- 首次有效绘制（FMP）
	- 每秒传输帧数（FPS）
	- 用户可交互时间
	- DNS解析时间
	- TCP连接时间
	- HTTP请求响应时间

- 评估工具

	- [PageSpeed](https://developers.google.com/speed/pagespeed/insights/?hl=zh-cn)
	- [WebPageTest](https://www.webpagetest.org/)
	- [PhantomJS](https://phantomjs.org/)
	- [Lighthouse](https://developers.google.com/web/tools/lighthouse)
	- [JSPerf](https://github.com/jsperf/jsperf.com)
	- [Chrome dev tools](https://developers.google.com/web/tools/chrome-devtools)

### 安全

- [XSS](https://zh.wikipedia.org/wiki/%E8%B7%A8%E7%B6%B2%E7%AB%99%E6%8C%87%E4%BB%A4%E7%A2%BC)
- [CSRF](https://zh.wikipedia.org/wiki/%E8%B7%A8%E7%AB%99%E8%AF%B7%E6%B1%82%E4%BC%AA%E9%80%A0)
- [CSP](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/CSP)
- [Same-origin Policy](https://developer.mozilla.org/zh-CN/docs/Web/Security/Same-origin_policy)

### 浏览器

- IE6/7/8/9/10/11 (Trident) / Edge (EdgeHTML)
- Firefox (Gecko)
- Chrome/Chromium (Blink)
- Safari (WebKit)
- Opera (Blink)
- 补：[can i use](https://caniuse.com/)

## 工程开发

### 模块化

- CSS Module
- ES6 Module
- CommonJS
- SeaJS/CMD
- RequireJS/AMD

### 版本管理

- Git

	- Gitlab
	- Github

- Svn

	- TortoiseSVN

### 依赖管理

- npm
- Yarn
- Lerna

### 语言增强

- CSS

	- less
	- Sass(Scss)
	- Stylus
	- Post css

- JavaScript

	- TypeScript
	- CoffeeScipt
	- Flow

### 构建工具

- Webpack
- Gulp
- Grunt
- Rollup

### 转换器

- Babel
- Traceur

### CI/CD

- Git web hook
- Jenkins

### 代码质量

- 质量检测

	- JSLint/JSHint/TSLint/ESLint
	- StyleLint
	- Sonar

- 单元测试

	- Chai/Expect/Should
	- Unit/Mocha/QUnit/Jasmine/Jest
	- Karma
	- Sinon
	- Istanbul

- E2E测试

	- Nightwatch
	- Cypress

## 编程思想

### 设计模式

- 单例模式
- 工厂模式
- 观察者模式
- 发布订阅模式
- 代理模式
- 适配器模式
- 策略模式
- 命令模式
- ...

### 架构模式

- Script
- Code Blocks
- Code Behind
- MVC
- MVP
- MVVM
- Flux

### 编程范型

- 面向对象编程（OOP）
- 面向切面编程（AOP）
- 函数式编程
- 响应式编程

### 程序设计

- 结构化程序

	- 自顶向下
	- 逐步求精
	- 模块化
	- 限制使用goto

- 面向对象程序

	- 单一功能原则（S）
	- 开放关闭原则（O）
	- 里氏替换原则（L）
	- 接口隔离原则（I）
	- 依赖反转原则（D）

## 领域分支

### 可视化

- SVG

	- D3
	- Raphaël
	- Snap

- Canvas 2D

	- Echarts
	- HighCharts

- WebGL

	- Three

### 移动Web

- WebView

	- Zepto
	- jQuery Mobile

- Web to Native

	- Weex
	- React Native
	- Flutter

- 小程序
- 响应式网页设计

### 游戏开发

- Cocos2d
- Egret Engine

### 便携式设备

- Glass
- Bracelet

## 社区发展

- SSR

- 大前端

- 微服务

- Serverless

- WebAssembly

- Less code/No code

## 计算机基础

### 编译原理

- 词法
- 文法
- V8
- AST

### 数据结构

- 堆（Heap）
- 栈（Stack）
- 队列（Queue）
- 链表（Linked List）
- 数组（Array）
- 树（Tree）
- 集合（Set）
- 哈希表（Map）

### 算法

- 排序

	- 冒泡排序
	- 选择排序
	- 插入排序
	- 快速排序
	- 希尔排序
	- 归并排序
	- 堆排序
	- 计数排序
	- 基数排序

- 检索

	- 线性搜索
	- 二分查找
	- 索引
	- 深度优先搜索（DFS）
	- 广度优先搜索（BFS）

- Diff

### 操作系统

- PC

	- Linux
	- Unix
	- Windows
	- Mac OS

- Mobile

	- Android
	- IOS

### 计算机网络

- OSI七层模型

## 后端知识

### Node

- Express
- Koa
- Egg

### 编程语言

- C/C++/Java/PHP/Ruby/Python/...

### 网页服务器

- Nginx
- Apache
- Tomcat

### 数据库

- SQL

	- MySQL
	- Oracle
	- SQL Server
	- PostgreSQL
	- DB2

- NoSQL

	- MongoDB
	- CouchDB
	- Hbase

### 数据缓存

- Redis
- Memcached

## 软技能

### 学习能力

- 知识储备
- 知识分享

### 技术能力

- 解决问题

### 团队协作

- 沟通技巧

### 项目管理

- 业务理解
- 需求分析
- 项目评估

### 人员管理

### 架构设计能力

- 交互设计
- 可用性
- 扩展性
- 安全性
- 性能

## 参考文献
* [进军高级前端开发工程师必备的知识图谱](https://segmentfault.com/a/1190000017849026)
* [前端技能汇总](https://github.com/JacksonTian/fks)