---
layout: comic
name: Index
title: Index
permalink: /
---

{% for post in site.posts limit:1 %}
  <img class="comic" src="/assets/comics/{{ post.comic_id }}.png" />
{% endfor %}