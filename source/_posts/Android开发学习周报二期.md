---
title: Android开发学习周报二期
date: 2018-12-10 16:59:50
tags: 周报
---
## 文章
[一. 美团外卖Android Crash治理之路](https://tech.meituan.com/waimai_android_crash.html)
1. 美团大厂的 Crash 治理手册，将App的Crash率从千分之三做到万分之二的实践
2. 符合近期公司质量提升计划，强烈推荐
3. 重点可读一下 NullPointerException、内存泄漏、AOP 方面的治理

<!--more-->
[二. 不到100行代码实现左右对齐TextView](https://mp.weixin.qq.com/s/cLhf-SSS3I5SkPEFd5Cxbw)
1. TextView 左右对齐的需求是常见需求，短小精悍，读来有趣有料
2. 喜欢这种从小处痛点出发，带我们源码一波游的操作

[三. Android下setTextSize的正确使用姿势](https://www.jianshu.com/p/7f2941dbfb17)
1. 新的屏幕方案也会用到
2. 理清楚 TextView#setTextSize 方法里，传入具体数字和从资源文件获取的数值之间的区别

[四. 代码整洁之道（一）最佳实践小结](http://url.cn/5NVfpA0)
1. 代码规范，对于提升代码可读性，可维护性有重要的作用
2. 相信每一个优秀的工程师都有一颗追求卓越代码的心

[五. Android应用程序UI硬件加速渲染技术简要介绍和学习计划](https://blog.csdn.net/Luoshengyang/article/details/45601143)
1. Android 5.0 以后屏幕绘制会更多的使用硬件加速，合理使用硬件加速对绘制效率影响很大
2. 硬件加速基本流程：将 View 作为 Render Node，将 drawxxx() 方法和参数存储到 Display List 中，以树形结构进行存储，使用 Open GL 在 Render Thread 进行绘制