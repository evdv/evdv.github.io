---
layout: default
title: Blog
permalink: /posts
---

## Musings and ramblings

<ul>
  {% for post in site.posts %}
  <li><a href="{{ post.url }}" class="post-preview">{{ post.title }}</a></li>
  {% endfor %}
</ul>
