# CrazyDaily
一款程序员日常放松的App，基于Material Design + MVP-Clean + Weex + RxJava2 + Retrofit + Dagger2 + Glide + Okhttp + MTRVA + 炫酷控件 + 炫酷动画

## 效果图
### 首页
文章：[带你领略Clean架构的魅力](http://crazysunj.com/2017/09/25/%E5%B8%A6%E4%BD%A0%E9%A2%86%E7%95%A5Clean%E6%9E%B6%E6%9E%84%E7%9A%84%E9%AD%85%E5%8A%9B/)

![](https://github.com/crazysunj/crazysunj.github.io/blob/master/img/app_crazydaily.gif)

### Weex
文章：[一起来玩Weex](http://crazysunj.com/2018/03/16/%E4%B8%80%E8%B5%B7%E6%9D%A5%E7%8E%A9Weex/)

![](https://github.com/crazysunj/crazysunj.github.io/blob/master/img/demo_weex.gif)

### 联系人

![](https://github.com/crazysunj/crazysunj.github.io/blob/master/img/crazydaily_anim.gif)

## 简介
* 知乎日报
* 干货集中营
* 天气
* 搞笑视频
* 联系人

## 技术点
* 架构采用MVP-Clean，项目简洁、易维护、易测试、高内聚、低耦合
* UI风格采用Material Design，清新、简洁和直观
* 跨端采用Weex，涉及weex页面、自定义Module、自定义Component、自定义Adapter等
* RxJava的操作符巧妙运用
* Dagger2与Butterknife实现依赖注解，解耦，方便测试等
* Retrofit和Okhttp实现网络架构，实现多种扩展，例如常见的日志规范打印，不用抓包，直接在日志中游览
* Glide实现图片加载，配合GlideTransformations实现多种变换，如圆角、遮罩等
* MTRVA轻松处理RecyclerViewAdapter的数据，实现多列表效果更佳
* 大量自定义控件，如Camera、Matrix、贝塞尔曲线、高斯模糊、Behavior、事件拦截等等运用
* 大量动画，如lottie、补间动画、3D动画、属性动画（ObjectAnimator、ValueAnimator、View.animate和PropertyValuesHolder）和转场动画（自定义Transition）运用
* 视频列表

尽量保持各种开源库最新状态，我踩坑，我骄傲！

有意见或者建议的同学可以联系我哦，持续更新，祝你生活愉快！

喜欢的朋友点个star关注一下我吧！

[下载地址](https://www.pgyer.com/EbHS "https://www.pgyer.com/EbHS")

想干的事（暂时先罗列这么多，版本迭代陆续实现，不分先后）：
* 网络加上缓存机制
* 加上引导页
* 添加图片查看，修改等
* 首页改为多fragment
* 添加微信精选，稀土掘金模块
* 游览器内核改为x5
* 视频列表支持小窗口播放
* WebView预加载

    ...

`[注]`本项目为开源项目，项目中涉及api若有侵犯产品权益，请告知，立刻删除。
## License

> ```
> Copyright 2017 Sun Jian
>
> Licensed under the Apache License, Version 2.0 (the "License");
> you may not use this file except in compliance with the License.
> You may obtain a copy of the License at
>
>    http://www.apache.org/licenses/LICENSE-2.0
>
> Unless required by applicable law or agreed to in writing, software
> distributed under the License is distributed on an "AS IS" BASIS,
> WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
> See the License for the specific language governing permissions and
> limitations under the License.
> ```