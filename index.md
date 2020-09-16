---
layout: default
title:  "Richard Marston's"
---
# it begins. or does it?

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
