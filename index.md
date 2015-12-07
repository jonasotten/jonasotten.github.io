---
layout: blog
title : Jonas Blog
---


## Jonas Blog
Hopefully some day I will write blog posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
