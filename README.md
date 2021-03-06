# AjaxLearningNodes （Ajax学习笔记）
> - [Ajax学习网站](http://www.runoob.com/ajax/ajax-tutorial.html)
- [Ajax中的同步和异步](http://www.cnmiss.cn/?p=84)
- [Ajax代码思路](http://www.cnblogs.com/venoral/p/5136508.html)
- [你真的会使用XMLHttpRequest吗](https://segmentfault.com/a/1190000004322487)

1. JavaScript处理Ajax的4个基本步骤
    - XMLHttpRequest的创建(不同浏览器创建XHR的区别)
    - open('get/post','url','true/false')参数的设置!(get/post请求的区别,参数的设置;true/false异步同步问题深究)
    - send(null/post参数);发送请求
    - onreadystatechange设置回调函数;回调函数设置在不同位置,有什么区别;readyState/status状态;
    - 响应数据的格式,设置响应数据注意的问题
    - Http header的设置;Http头是什么,http头的作用
    - 扩展:深入了解XMLHttpRequest对象;get、post区别;onreadystatechange深究
2. JQuery中的Ajax [jQuery中$.get、$.post、$.getJSON、$.ajax 方法详解](http://blog.csdn.net/huileiforever/article/details/12163385)
    * load 
    * get
    * post
    * getJSON、getScript
    * ajax
    * jQuery.ajaxSetup
    * 全局事件处理:ajaxComplete()、ajaxError()、ajaxSend()、ajaxStart()、ajaxStop()、ajaxSuccess()
    * 辅助函数serialize、serializeArray、jQuery.param
    * **JQuery中的Deferred(延时对象)  [阮一峰:jQuery的deferred对象详解](http://www.ruanyifeng.com/blog/2011/08/a_detailed_explanation_of_jquery_deferred_object.html)**
        - done,fail,then,always
        - deferred状态
        - .promise()
        - 多个ajax绑定一个事件,一个ajax绑定多个事件
3. fastJSON,jackson,xStream使用
    * [Json解析教程](http://zyjustin9.iteye.com/blog/2020533)
    * [fastJson](http://www.cnblogs.com/zhenmingliu/archive/2011/12/29/2305775.html)
    * fastJSON中javaBean的序列化/反序列化,集合、泛型、组合类型的反序列化,SerializerFeature常用配置,日期的格式化
    * jackson的日常。。。
    * xStream中XML的操作,JavaBean<-->XML,xStream中对节点的修改处理
4. 扩展
    * 回顾java IO操作(File<-->String)
    * JavaScript中节点的操作
5. 练习
    * JS操作XML的省市联动(基于节点/基于XPath)
    * JQuery操作XML的省市联动(自定义的插件)
    * JQuery滚动加载
    
    