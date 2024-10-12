---
layout: page
title: Blog
permalink: /blog/
---

{% for post in site.posts %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
    <p><small>{{ post.date | date: "%B %d, %Y" }}</small></p>
  </article>
{% endfor %}

