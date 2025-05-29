---
layout: default
title: Home
---

# Welcome to My IT Blog

Here you'll find tutorials, troubleshooting notes, and tools for sysadmins, developers, and automation enthusiasts.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — *{{ post.date | date: "%B %d, %Y" }}*
{% endfor %}
