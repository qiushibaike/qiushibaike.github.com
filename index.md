---
layout: page
title: 糗事百科 &hearts; Open Source
tagline: 
---
{% include JB/setup %}

### Bonjour!
这里是就是正版糗百github仓库

我们的官网 -> [糗事百科](http://www.qiushibaike.com) 

开源项目列表 -> [https://qiushibaike.github.com](https://github.com/qiushibaike) 


### Blogs    

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



