
---
layout: default
title: Home
---

# Hi, it is Olga

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <h3>
        <a href="/blog/2024/03/19/first-post.html">{{ post.title }}</a>
      </h3>
      <p>{{ post.date | date: "%B %d, %Y" }}</p>
      {% if post.description %}
        <p>{{ post.description }}</p>
      {% endif %}
    </li>
  {% endfor %}
</ul> 