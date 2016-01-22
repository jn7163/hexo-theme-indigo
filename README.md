hexo-theme-material-indigo
================

Material Design 风格的Hexo主题，基于 Hexo 3.0+ 制作。预览 [我的博客](http://www.imys.net/)

## 特色

1. 仅支持 IE10+ 等现代浏览器。难道还有程序猿用 IE < 9 吗？
2. 去 jQuery。仅仅 100+ 行js代码，还需要 jQuery 吗？
3. 去 fancybox。没了 jQuery, 这个自然也失效了。
4. 使用 Less 作为 css 预处理器，需要安装 `hexo-renderer-less`。
5. 添加了英文字体支持 Roboto。
6. 添加了一些波纹效果。By [Waves](https://github.com/fians/Waves)
7. 分享直接使用了 JiaThis API 接口，免去了一次加载请求。

## 截图

### PC

![indigo-pc](https://github.com/yscoder/hexo-theme-indigo/raw/master/screenshots/hexo-theme-pc.png)

### Pad

![indigo-pad](https://github.com/yscoder/hexo-theme-indigo/raw/master/screenshots/hexo-theme-pad.png)

### Phone

![indigo-phone-1](https://github.com/yscoder/hexo-theme-indigo/raw/master/screenshots/hexo-theme-phone-1.png)
![indigo-phone-2](https://github.com/yscoder/hexo-theme-indigo/raw/master/screenshots/hexo-theme-phone-2.png)

## Config

```
# Header
menu:
  home:
    url: /
  archives:
    url: /archives
  tags:
    url: /tags
  github:
    url: https://github.com/yscoder
    target: _blank
  weibo:
    url: http://www.weibo.com/ysweb
    target: _blank

rss: /atom.xml

#你的头像url
avatar: /img/logo.jpg

# Content
tags:
  title: 标签

excerpt_link: more
mathjax: false
archive_yearly: true

#是否开启分享
share: true
#是否开启toc
#toc: false
toc:
  list_number: false  # 是否显示数字排序

# Miscellaneous
google_analytics: ''
favicon: /favicon.ico

# less
less:
  paths:
    - source/css/style.less


#是否开启多说评论，填写你在多说申请的项目名称 duoshuo: duoshuo-key
#若使用disqus，请在博客config文件中填写disqus_shortname，并关闭多说评论
duoshuo: ysblog
```
