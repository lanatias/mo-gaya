---
layout: page
title: Mo-gaya Engineering Blog
tagline: Mo-gaya
---
{% include JB/setup %}

Welcome to Mo-gaya development blog. 

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


