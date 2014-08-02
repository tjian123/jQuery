jQuery
======

jQuery源码分析

  源码分析博客
  www.cnblogs.com/AaronJs

  
  
  jQuery源码分析目录（2.1.1版本）
								
                                By 2014
大家最关注的问题，我能学到什么？
本书围绕的几个核心点：
1.	设计理念
2.	结构组织
3.	抽象设计
4.	模式运用
5.	场景套用

第一章：语言基础
    1.1	基本类型与引用类型
    1.2	参数的值传递
    1.3	执行环境与作用域链
    1.4	理解原型链
    1.5	理解闭包
    1.6	理解类继承
    1.7	面向对象设计

第二章：设计模式
    2.1	单体模式
    2.2	门面模式
    2.3	工厂模式
    2.4	观察者模式
    2.5	中介模式
    2.6	适配器模式
    2.7	装饰者模式
    2.8	桥接模式
    2.9	组合模式
    2.10代理模式

第三章：理解jQuery
    3.1	库与框架
    3.2	jQuery的定位
    3.3	初步认识jQuery
        3.3.1	jQuery与dom对象的区别
        3.3.2	基础设施模块
        3.3.3	选择器模块
        3.3.4	节点模块
        3.3.5	AJAX模块
        3.3.6	动画模块
        3.3.7	其余的扩展
    3.4	jQuery使用的设计手法
    3.5	不经意的模式
    3.6	 jQuery 引入的模式
    3.7	 jQuery的高级运用


第四章：核心模块
    4.1	理解静态与实例
    4.2	无new构建
    4.3	如何分离作用域
    4.4	方法的链式调用
    4.5	插件接口
    4.6	设计一个jQuery的原型库

第五章：回调函数
	5.1 运用场景
	5.2 设计思路
	5.3 简单实现
	5.4 jQuery实现

第六章：数据缓存
	6.1	缓存介绍
	6.2	jQuery引入缓存中解决的问题
	6.3	运用场景
	6.4	jQuery Data数据缓存实现

第七章：异步机制
	7.1	介绍
	7.2	理解同步与异步差别
	7.3	深入定时器
	7.4	实际运用中的处理
	7.5	简单模型的实现
	7.6	原理剖析
	7.7 	jQuery.Deferred实现
	
第八章：模块加载
	8.1	AMD与CMD规范
	8.2	如何设计
	8.3	轻巧的实现

第九章：选择器引擎
	9.1	css选择器
	9.2	浏览器提供的接口与兼容问题
		9.2.1	getAttribute和getAttributeNode
		9.2.2	关于querySelectorAll兼容问题
	9.3	选择器引擎设计的思路与知识点 
	9.4	正则表达式分解
	9.5	解析sizzle引擎
		9.5.1	词法解析器
		9.5.2	解析原理
		9.5.3	编译函数
		9.5.4	超级匹配
		9.5.5	属性选择器
		9.5.6	伪类选择器

第十章：文档处理
    10.1节点层次关系的理解
    10.2忽略的细节
        10.2.1	Document.body与DocumentElement区别
        10.2.2 	contentWindow、contentDocument、document区别
        10.2.3   DocumentFragment存在的问题
        10.2.4	iframe存在的问题
        10.3.5	HTML5引入的高级API
    10.3 DOM操作技术
        10.3.1	创建节点
        10.3.2	插入节点
        10.3.3	删除节点
        10.3.4	替换节点
    10.4 Query文档处理
        10.4.1	整体思路
        10.4.2	内部插入
        10.4.3	外部插入
        10.4.4	包裹
        10.4.5 	替换
        10.4.6	删除
        10.4.7	复制


第十一章：样式操作
	11.1 样式操作的规则
		11.1.1 样式访问接口
		11.1.2 不同浏览下的兼容性
		11.1.3 注意细节
	11.2 标准操作
		11.2.1 样式表操作
		11.2.2 元素大小
		11.2.3 几种常见API的区别
	    11.2.4 jQuery样式操作
	11.3 位置
	11.4 尺寸

第十二章：属性操作
	12.1 属性与特性
	

第十三章：事件
	13.1 事件概述
	13.2 事件流与缺陷
	13.3 事件系统设计需要考虑的问题
	13.4 jQuery事件体系结构	
	13.5 jQuery中bind/live/delegate/on的区别
	13.6 jQuery绑定设计
	13.7 jQuery委托设计
	13.8 jQuery自定义事件设计
	13.9 jQuery模拟事件 
	
第十四章：AJXA
    14.1 整体结构
    14.2 Deferred实现
    14.3 前置过滤器与请求分发器
    14.4 预处理jsop
    14.5 Jsop的原理与实现
    14.6 类型转化器
    14.7 总结

第十五章：动画
	15.1 队列操作
	15.2 动画队列
	15.3 动画原理
	
第十六章：前端架构开发实战经验总结
    16.1 大型应用如何架构？
    16.2 分层设计
    16.3 运行设计模式
    16.4 异步与同步的处理
    16.5 单线程模拟多线程
    16.6 音频线程问题
		
	
			
