---
layout: default
title: 首页
---

<!-- 欢迎语：仅保留字号/间距（局部样式），字体继承全局style.scss的微软雅黑 -->
<p style="font-size: 24pt; margin: 20pt 0;">
  欢迎来到我的网站！
</p>

<!-- 关于链接：仅保留字号/颜色（局部样式），字体自动继承 -->
<p>
  <a href="{{ '/about.md' | relative_url }}" style="
    font-size: 20pt;
    color: #3498db;
    text-decoration: none;
  ">关于</a>
</p>