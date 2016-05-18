# BaiduNaviSDKDemo
---

## 基本用法

基本用法见 demo

<img src="https://cloud.githubusercontent.com/assets/7868514/15351503/27de26bc-1d12-11e6-9697-9058afb00d40.png" width="320"/>
<img src="https://cloud.githubusercontent.com/assets/7868514/15351502/27dcbf70-1d12-11e6-8d66-e9510df9f26f.png" width="320"/>

## 自定义导航 View

自定义的话，添加导航 View 到自己布局就可以了：

```
setContentView(R.layout.activity_scrolling);

//把导航的 view 添加到自己布局里
addContentView(view, new ViewGroup.LayoutParams(1600, 1000));
```
<img src="https://cloud.githubusercontent.com/assets/7868514/15358588/b1193b4a-1d37-11e6-8a40-acaa9f24b233.png" width="640" />