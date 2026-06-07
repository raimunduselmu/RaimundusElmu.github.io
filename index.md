---
layout: default
title: Home
---

## Artikel Terbaru

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> — <i>{{ post.date | date: "%d %B %Y" }}</i>
    </li>
  {% endfor %}
</ul>
