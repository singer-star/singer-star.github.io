## 云南大学美食美景展示

基于Jekyll的目录，HTML5，CSS，JavaScript编写

### Features 特性

- 代码高亮
- 夜间模式
- 粉蓝两种主题色
- 头图个性化底纹
- 响应式设计
- SEO标题优化
- 文章标签索引
- 文章搜索
- 复制文章内容自动添加版权

### 站点信息

可以通用修改 `_config.yml` 文件修改相关内容

### 后台发布其他展示内容

文章一般都放在`_posts`文件夹里，每篇文章的开头都需要设置一些头信息：

---
layout: post
title: 'xxx'
subtitle: '相关描述'
date: 2021-06-18
tags: jekyll
---

### 导航

导航栏信息需要以下面的格式进行配置：

#### Navigation links
nav:
  home: '/'
  food: '/food.html'
  scenery:'scenery.html'

### 侧边栏

侧边栏分当屏幕宽度小于960px时，侧边栏会被隐藏。

### 云大其他社交网站图标

#### SNS settings 配置网站url
sns:
  zhuhu: '//www.zhihu.com/'
  weibo: '//weibo.com/'

### 标签

对侧边栏的标签模块进行相应配置：

#### Tags
recommend-tags: true
recommend-condition-size: 12

### 文章搜索

基于Jekyll服务器生成文章索引文件 `search.json` 为博客提供搜索服务。输入文章标题或与文章标签相关的关键字即可。

搜索功能默认是开启的，以卡片的样式显示在侧边栏底部。如需关闭请将配置文件 `_config.yml` 中 `search ` 属性的值改为 `false` 。

### 夜间模式

晚11点至次日凌晨6点自动开启夜间模式。如果不需要，则将配置文件 `_config.yml` 中 `nightMode ` 属性的值改为 `false` 即可。

### 主题皮肤

支持两种主题颜色蓝色和粉色

颜色 | 参数
----|-----
蓝色 | `default`
粉色 | `pink`

### 头图底纹

#### Hero background patterns
postPatterns: 'circuitBoard'

`postPatterns` 属性参数配置：

底纹描述  |  参数
------|------
电路 | `circuitBoard`
圆环 | `overlappingCircles`
吃货日常：啃打鸡 | `food`
土豪必备：钻石| `glamorous`
圈圈叉叉 | `ticTacToe`
中国风：云海 | `seaOfClouds`

### 结构目录




