---
layout: default
title: Tips and Samples
---

<div id="home">
  <h1>Tips & Sample</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

</div>
