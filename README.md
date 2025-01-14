# shopec-b2b2c-release
专注为个人及企业打造易用的B2B2C电商平台

#### 项目介绍
该商城是一个综合性的B2B2C平台，类似天猫商城。用户可以在商城浏览商品、下订单，以及参加各种活动。该商城采用Spring Boot+MyBatis框构，为了提高系统的性能使用Ehcache做系统缓存，搜索功能使用Elasticsearch做搜索引擎。

## 系统架构图

![输入图片说明](https://images.gitee.com/uploads/images/2019/0420/101749_70739496_460606.jpeg "系统架构图")

## 功能列表

 _1、管理平台_ 

【店铺管理】商家管理、店铺管理、店铺分类、店铺等级、商家注册项、提现管理、经营分类申请、商家预存款

【商品管理】商品管理、库存管理、商品分类、商品标签、商品参数、商品属性、规格管理、品牌管理

【订单管理】订单管理、订单支付、订单退款、订单发货、订单退货、发货点管理、快递单模板

【会员管理】会员等级、会员注册项、积分管理、会员预存款、评论管理、咨询管理、消息配置

【内容管理】导航管理、文章管理、文章分类、文章标签、友情标签、友情链接、广告位、广告管理、模板管理、缓存管理

【营销管理】促销管理、优惠券管理、SEO设置

【系统设置】系统设置、地区管理、支付方式、配送方式、物流公司、支付插件、存储插件、登录插件、管理员、角色管理、发送消息、草稿箱、审计日志

 _2、商家中心_ 

【商品管理】商品列表、库存记录、到货通知、商品咨询、商品评论

【订单管理】订单列表、快递单模板、发货点管理

【店铺管理】店铺设置、店铺商品分类、店铺商品分类、经营分类申请、店铺缴费、配送方式、店铺广告图片

【促销管理】折扣促销、满减促销、优惠券

【预存款管理】预存款充值、预存款提现、预存款记录

【个人资料】个人资料、密码修改

【统计信息】订单统计、商品排名

 _3、会员中心_ 

【交易信息】我的订单、我的优惠券、我的积分

【我的收藏】商品收藏、店铺收藏、到货通知、商品评论、商品咨询

【我的消息】发送消息、我的消息、草稿箱

【个人资料】个人资料、修改密码、收货地址、帐户绑定、

【预存款】预存款充值、我的取存款


## 技术选型

1、后端

* 核心框架：Spring Boot 2.1.4.RELEASE
* 安全框架：Apache Shiro 1.4.0
* 视图框架：Spring MVC 5.1.6.RELEASE
* 搜索框架：Elasticsearch 6.4.3
* 任务调度：Spring + Quartz 2.2.3
* 持久层框架：MyBatis 3.4.6 + Mybatis-plus 3.0.7.1
* 数据库连接池：Alibaba Druid 1.1.14
* 缓存框架：Ehcache 2.6 + Redis 2.9.0
* 日志管理：SLF4J 1.7 + Log4j2 2.7
* 工具类：Apache Commons、Jackson 2.9.6、fastjson 1.2.6
* JWT实现oauth2服务
* social实现微信登录
    

2、前端
* JS框架：Jquery
* 表格插件：Bootstrap Table
* 表单验证插件：Jquery.Validate
* 日期选择插件：Datepicker for Bootstrap
* 数据图表：Echarts
* 后台管理系统模版：AdminLTE

## 快速体验

> 运行项目配置说明

1.后台管理系统

```
1、具备运行环境：JDK1.8+、Maven3.0+、MySql5.6+

2、根据 src\main\resources\application-dev.yml 配置数据库

3、导入数据库 shopecb2b2c.sql

4、安装Elasticsearch，application.yml 中修改配置地址

5、选中ApplicationB2B2C.java右击 -> Run As -> Java Application

6、后台管理系统账号：admin 密码：123456

7、商家管理系统账号：shopec_sj 密码：123456

## 特别说明

详细操作手册、演示Demo请与我们联系：扣扣 187048359
