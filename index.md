---
layout: index
title: index
tagline:
---

{% include JB/setup %}

最近更新

{% for post in site.posts limit:10 %}
{{ post.date | date_to_string }} » {{ post.title }}
{% endfor %}
