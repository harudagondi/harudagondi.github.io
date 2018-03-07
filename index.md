---
layout: default
title: don't even go here
---

# hello

It's just rants of a certain highschooler.

___

{% for post in site.posts %}

[{{ post.title }}]({{post.url}})
----------------

{{ post.content | strip_html | truncatewords: 28 }}

___

{% endfor %}
