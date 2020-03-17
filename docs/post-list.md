---
title: All Posts
toc: true
---

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }}) - {{ post.date | date: '%B %d, %Y' }}
{% endfor %}