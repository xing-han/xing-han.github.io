---
layout: home
title: 聪明的鱼鱼和她の男人
---

{% for post in site.posts %}
<li class="list-group-item title">
    <div class="date">{{post.date | date:"%Y年%m月%d日"}}</div><br>
    <a href="{{ post.url | remove: '.html' }}"> {{post.title}} </a>
</li>
{% endfor %}
