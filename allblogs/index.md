---
layout: default
title: Demi's Blog Index
---
<h1>{{ page.title }}</h1>
This is the complete listing of all my blogs.
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

