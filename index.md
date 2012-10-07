---
layout: page
title: X-Factor of Freedom
tagline: 
---
{% include JB/setup %}

##About me

![about me]({{ BASE_PATH }}/images/11.jpg)

我目前是浙江大学CAD&CG国家重点实验的在读研究生。热爱骑行，热爱技术！我不会让我的热血消失在我的思想中，让我们用激情来体验这个美好世界吧~~~

##Archive

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
