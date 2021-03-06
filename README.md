## last studying address
https://yuchengkai.cn/docs/frontend/safety.html

## --html
1. [HTML5 新特性](https://www.cnblogs.com/vicky1018/p/7705223.html)

## --css
1. [一个元素垂直居中的方式，至少三种](https://www.cnblogs.com/SRH151219/p/10401489.html)
1. [BFC 块格式化上下文](https://www.cnblogs.com/SRH151219/p/10401285.html)
1. [flex布局](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)
1. flex实现瀑布流
1. [px、rem、em](http://www.runoob.com/w3cnote/px-em-rem-different.html)

## --js
1. [创建一个对象的过程](https://yuchengkai.cn/docs/frontend/#new)
1. [new 运行优先级](https://yuchengkai.cn/docs/frontend/#new)
    ```js
    function Foo() {
        return this;
    }
    Foo.getName = function () {
        console.log('1');
    };
    Foo.prototype.getName = function () {
        console.log('2');
    };

    new Foo.getName();   // -> 1
    new Foo().getName(); // -> 2
    ```
1. [手动实现instanceof](https://yuchengkai.cn/docs/frontend/#instanceof)
1. [this 的绑定、箭头函数与 this](https://www.cnblogs.com/snandy/p/4773184.html)
1. [手写 bind this](https://blog.csdn.net/qq_40479190/article/details/78324282)
1. [手写一个 new](https://yuchengkai.cn/docs/frontend/#new)
1. [闭包————解决循环中调用异步操作的问题，三种解决方式](https://yuchengkai.cn/docs/frontend/#%E9%97%AD%E5%8C%85)
1. [深拷贝、浅拷贝的方法](https://yuchengkai.cn/docs/frontend/#%E6%B7%B1%E6%B5%85%E6%8B%B7%E8%B4%9D)
1. [防抖](https://yuchengkai.cn/docs/frontend/#%E9%98%B2%E6%8A%96)
1. [节流](https://yuchengkai.cn/docs/frontend/#%E8%8A%82%E6%B5%81)
1. [call, apply, bind 区别及模拟实现](https://yuchengkai.cn/docs/frontend/#call-apply-bind-%E5%8C%BA%E5%88%AB)
1. [promise、generator、async await等异步解决方案](https://www.cnblogs.com/zuobaiquan01/p/8477322.html)(http://www.cnblogs.com/wangfupeng1988/p/6513070.html)
1. [存储](https://yuchengkai.cn/docs/frontend/browser.html#%E5%AD%98%E5%82%A8) (拓展：https://www.jianshu.com/p/10bbff64ccab)
1. []
1. [service-worker](https://yuchengkai.cn/docs/frontend/browser.html#service-worker)

## --react redux
1. [为什么要使用redux](https://github.com/kenberkeley/redux-simple-tutorial)
1. [React16新的生命周期函数getDerivedStateFromProps](https://blog.csdn.net/nnxxyy1111/article/details/80832525)
1. [React v16新特性](https://yuchengkai.cn/docs/frontend/react.html#react-%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F%E5%88%86%E6%9E%90)：
    StrictMode、fiber、新的生命周期函数、Context、新的render、Fragment、ref=>React.createRef()、Portals组件、错误处理(componentDidCatch)等
1. setState异步操作
1. [redux 源码分析](https://yuchengkai.cn/docs/frontend/react.html#redux-%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90)

## --框架、设计模式
1. MVC
1. [MVVM](https://yuchengkai.cn/docs/frontend/framework.html#mvvm)
    (1. [angular脏检查机制](https://yuchengkai.cn/docs/frontend/framework.html#%E8%84%8F%E6%95%B0%E6%8D%AE%E6%A3%80%E6%B5%8B)；2. [vue数据劫持](https://yuchengkai.cn/docs/frontend/framework.html#%E6%95%B0%E6%8D%AE%E5%8A%AB%E6%8C%81))
1. [手写订阅发布模式](https://www.jianshu.com/p/ea671156baf5)
1. babel loader详解以及手写babel loader(https://segmentfault.com/a/1190000014205729)(https://segmentfault.com/a/1190000011524373/)
1. [路由原理](https://yuchengkai.cn/docs/frontend/framework.html#%E8%B7%AF%E7%94%B1%E5%8E%9F%E7%90%86)
1. [Virtual Dom](https://yuchengkai.cn/docs/frontend/framework.html#%E4%B8%BA%E4%BB%80%E4%B9%88%E9%9C%80%E8%A6%81-virtual-dom)

## --硬知识
1. 浏览器缓存
1. [js继承模式](https://yuchengkai.cn/docs/frontend/#%E7%BB%A7%E6%89%BF)
1. 输入url发生了什么
    1. (缓存：https://juejin.im/post/5c6e77da6fb9a049db73bb07)
    1. (一，同上、https://juejin.im/post/5c4e5250518825260c5d1f63)
    1. (二，解析、https://juejin.im/post/5c72a870e51d4541e37db4b3)
1. [十分钟读懂浏览器渲染流程](https://blog.csdn.net/farsight1/article/details/79758347)
1. [前端阶段性总结（一）： HTTP 协议，从1.0到2.0（他的主页其他博客也需阅读）](https://segmentfault.com/a/1190000016179430)
1. [前端阶段性总结（二）：页面渲染机制与性能优化](https://segmentfault.com/a/1190000016458627)
1. [前端阶段性总结（三）：web安全](https://segmentfault.com/a/1190000016490817)
1. [深度解析原型中的各个难点](https://github.com/KieSun/Dream/issues/2)
1. 模块化(https://yuchengkai.cn/docs/frontend/#%E6%A8%A1%E5%9D%97%E5%8C%96)(https://www.cnblogs.com/SRH151219/p/10200752.html)
1. 同源策略以及跨域方式(https://yuchengkai.cn/docs/frontend/browser.html#%E8%B7%A8%E5%9F%9F)(https://segmentfault.com/a/1190000011145364)
1. 跨域的解决方案(https://segmentfault.com/a/1190000011145364)
1. event loop(https://yuchengkai.cn/docs/frontend/browser.html#event-loop)(视频：https://video.tudou.com/v/XMjQ1OTczODMyMA==.html?__fr=oldtd)(案例：https://juejin.im/post/5a6155126fb9a01cb64edb45)(https://juejin.im/post/59e85eebf265da430d571f89)
1. [event 英文带动画](https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules/)
1. 为什么css3比修改height left等属性做动画性能更好？
1. translate3D为什么比translate性能更高？
1. [重绘、重排/回流](https://yuchengkai.cn/docs/frontend/browser.html#%E9%87%8D%E7%BB%98%EF%BC%88repaint%EF%BC%89%E5%92%8C%E5%9B%9E%E6%B5%81%EF%BC%88reflow%EF%BC%89)
1. [如何减少重绘、回流](https://yuchengkai.cn/docs/frontend/browser.html#%E5%87%8F%E5%B0%91%E9%87%8D%E7%BB%98%E5%92%8C%E5%9B%9E%E6%B5%81)
1. [缓存：强缓存、协商缓存](https://yuchengkai.cn/docs/frontend/performance.html#%E7%BC%93%E5%AD%98)
1. [性能优化](https://yuchengkai.cn/docs/frontend/performance.html#%E6%80%A7%E8%83%BD)
1. 性能优化方向：
    1. DNS预解析
    1. 缓存策略(强缓存，协商缓存，service worker首屏缓存)
    1. http2.0
    1. 预加载
    1. 预渲染
    1. 渲染过程(避免阻塞，避免重绘回流)
    1. 懒执行
    1. 懒加载(图片，视频等)
    1. 图片优化(css代替图片，cdn加速，尺寸适配，小图base64，雪碧图，svg代替png等)
    1. 其他文件优化(css放head，script放body底部，js耗能阻塞执行启用webworker)
    1. CDN加速，多CDN服务器突破并行下载数量上限
    1. webpack优化(代码压缩、tree shaking去除没使用的代码、小图base64、拆分路由按需加载、打包文件加哈希实现浏览器缓存文件)
    1. [参考自己的简书博客](https://www.jianshu.com/p/44146f8c0137)
1. [使用chrome开发者工具中的performance面板解决性能瓶颈](https://www.cnblogs.com/xiaohuochai/p/9182710.html)
1. [JavaScript如何一次性展示几万条数据
](https://blog.csdn.net/leipanbo/article/details/79894912)
1. web网络安全
    1. [XSS攻击](https://my.oschina.net/meituantech/blog/2218539)
    1. [CSRF攻击](https://my.oschina.net/meituantech/blog/2243958)
    1. [内容安全策略:CSP](https://linux.cn/article-5848-1.html)
    1. [密码安全](https://yuchengkai.cn/docs/frontend/safety.html#%E5%AF%86%E7%A0%81%E5%AE%89%E5%85%A8)
1. [浏览器跨页签通信](https://www.nowcoder.com/ta/review-frontend/review?tpId=80&tqId=29699&query=&asc=true&order=&page=22)
1. [实现一个圆形点击区域](https://www.nowcoder.com/ta/review-frontend/review?tpId=80&tqId=29700&query=&asc=true&order=&page=23)
1. [ref与src区别](https://www.nowcoder.com/ta/review-frontend/review?tpId=80&tqId=29704&query=&asc=true&order=&page=27)
1. [http与https区别](https://www.nowcoder.com/ta/review-frontend/review?tpId=80&tqId=32003&query=&asc=true&order=&page=73)
1. [iframe以及缺点](https://www.nowcoder.com/ta/review-frontend/review?tpId=80&tqId=32018&query=&asc=true&order=&page=88)
1. [get post区别](https://www.nowcoder.com/ta/review-frontend/review?tpId=80&tqId=32067&query=&asc=true&order=&page=137)
1. [实现sleep效果](https://www.nowcoder.com/ta/review-frontend/review?tpId=80&tqId=32167&query=&asc=true&order=&page=237)

## --软知识
1. 谈谈你的工作流程。
1. 谈谈你印象最深刻的一个bug。
1. 谈谈你印象最深刻的一个项目。
1. 谈谈你最满意的一个项目。

## --汇总篇
1. [前端面试的总结: 关于http+TCP+性能的优化](https://blog.csdn.net/weixin_41646716/article/details/79988249)
1. [Weekly-FE-Interview周刊](https://github.com/airuikun/Weekly-FE-Interview)
1. [原生JS知识点整理（必备基础）](https://juejin.im/post/5cb7b62b5188253772753c01)
1. [前端面试查漏补缺，大知识块](https://juejin.im/post/5c6bab91f265da2dd94c9f9e)

## INTERVIEW MAP ADDRESS
1. --[JS | InterviewMap](https://yuchengkai.cn/docs/frontend/)
1. --[前端面试经典题目合集（HTML+CSS）_牛客网](https://www.nowcoder.com/ta/review-frontend?query=&asc=true&order=&page=1)
1. [前端面试经典题目合集_牛客网](https://www.nowcoder.com/ta/front-end-interview)
1. [qiu-deqing/FE-interview: 收集的前端面试题和答案](https://github.com/qiu-deqing/FE-interview)
1. [我现在的情况应该怎么学习前端? - 知乎](https://www.zhihu.com/question/29382690)
1. [yygmind/blog: 我是木易杨，公众号「高级前端进阶」作者，跟着我每周重点攻克一个前端面试重难点。接下来让我带你走进高级前端的世界，在进阶的路上，共勉！](https://github.com/yygmind/blog)
1. [前端HR告诉你—如何面试Web前端开发](https://www.douban.com/group/topic/96092329/)
1. [2017年前端面试题整理汇总100题 - CSDN博客](https://blog.csdn.net/kebi007/article/details/54882425)
1. [阿里、网易、滴滴共十次前端面试碰到的问题 - WEB前端 - 伯乐在线](http://web.jobbole.com/91429/?utm_source=blog.jobbole.com&utm_medium=relatedPosts)
1. [React 常见的面试题 - CSDN博客](https://blog.csdn.net/sinat_17775997/article/details/69938720)
1. [Javascript的继承与多态 - 简书](https://www.jianshu.com/p/5cb692658704)
1. [前端开发js函数式编程真实用途体现在哪里？ - 知乎](https://www.zhihu.com/question/59871249)
1. [前端开发面试题+答案](https://github.com/markyun/My-blog/tree/master/Front-end-Developer-Questions/Questions-and-Answers)
1. [react原理等高级知识](https://github.com/purplebamboo/blog/issues)
1. [深度解析原型中的各个难点 · Issue #2 · KieSun/Dream](https://github.com/KieSun/Dream/issues/2)
1. [函数式编程在Redux/React中的应用 - 美团技术团队](https://tech.meituan.com/2017/10/12/functional-programming-in-redux.html)
1. [qiu-deqing/FE-interview: 收集的前端面试题和答案](https://github.com/qiu-deqing/FE-interview)
