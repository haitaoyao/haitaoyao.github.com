---
layout: page
title: Haitao Yao technical blog
tagline: share some thoughts about things working on
---

## Old blog:
[Here in Chinese](http://blog.csdn.net/aliveTime)

## Contents
<section id="article">
  <ul>
    {% for post in site.posts %}
      <li><time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_string }}</time> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</section>
