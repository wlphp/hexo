---
title: 鹿友会接口文档说明
date: 2021-01-01 22:19:37
tags:
---


# 鹿友会jsapi接口
使用第三方框架：https://github.com/wendux/DSBridge-Android

 :joy:  :joy:  :joy: :astonished:  :astonished:  :astonished: 
![输入图片说明](https://images.gitee.com/uploads/images/2018/1106/192209_383a6036_764892.png "201805261504151794.png")
#### 项目介绍
鹿友会jsapi接口文档，h5和安卓以及苹果进行交互。


#### 使用说明

1.1 行程首页=>目的地搜索接口

dsBridge.call("goDestinationSearch",{}, function (res) {
					
})

1.2 行程首页=>广告跳转接口

dsBridge.call("goAd",{parameter:parameter,'type':"carousel"}, function (res) {
					
})

 1.3 行程首页=>出境游、国内游、周边游、主题游、签证、门票、定制游、商城、充值

dsBridge.call("goCat",{parameter:parameter}, function (res) {
					
})

 1.4 行程首页=>右上角的二维码

dsBridge.call("goQrCode",{}, function (res) {
    
})

1.5 行程首页=>轮播图下面公告

 dsBridge.call("goAnnouncement",{parameter:parameter}, function (res) {
					
})

1.6 行程首页=>行程产品：秒杀专区、鹿友专区产品、品质专区、常规专区

dsBridge.call("goProduct",{parameter:parameter}, function (res) {
					
    
})

1.7 行程首页=>商城产品：商城推荐

dsBridge.call("goGood",{parameter:parameter}, function (res) {
					
})

 1.8 行程首页=>行程产品更多：秒杀专区、鹿友专区产品、品质专区、常规专区

dsBridge.call("goProductMore",{type:"miaosha、zhuanqu、pinzhi、changgui"}, function (res) {
					
})

1.9商城首页=>商品二级分类

dsBridge.call("goGoodCat",{parameter:parameter}, function (res) {
					
})

2.0商城首页=>常规商品详情
dsBridge.call("goGood",{parameter:parameter}, function (res) {
					
})

2.1商城首页=>限时抢购商品详情

dsBridge.call("goFlashSaleGood",{parameter:parameter}, function (res) {
					
})

2.2商城首页=>拼团商品详情

dsBridge.call("goCollageGood",{parameter:parameter}, function (res) {
					
})

2.3商城首页=>限时抢购更多、推荐更多、拼团更多、底部更多

dsBridge.call("goGoodMore",{type:"xianshi、tuijian、pintuan、dibu"}, function (res) {
					
})

2.4商城首页=>广告跳转

dsBridge.call("goShopAd",{parameter:parameter,'type':"carousel"}, function (res) {
					
})

2.5商城首页=>商品搜索

dsBridge.call("goGoodSearch",{}, function (res) {

})


2.6 APP返回上一页
 
dsBridge.call("goBack",{}, function (res) {

})

2.8web定位

dsBridge.call("getLocation",{}, function (res) {
    
})