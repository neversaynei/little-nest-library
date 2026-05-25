---
layout: default
title: Projects
---

# the library shelves

choose a story to begin your journey !

<div class="shelf">

{% for project in site.projects %}
  <a class="book-card" href="{{ project.url }}">
    <div class="book-title">{{ project.title }}</div>
    <div class="book-meta">{{ project.genre }}</div>
    <div class="book-status">{{ project.status }}</div>
  </a>
{% endfor %}

</div>