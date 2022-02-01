---
layout: default
author: "jonjab"
title: "About this website in the YAML HEADER"
---


# About my website
This is a website for a Carpentry workshop.

[Go Home](index.md)

# About loops

{% for there in a list %}
[        ]

{% endfor %}

## Blog posts
{% for post in site.blogposts %}
- {{ post.date | date_to_string }}: [{{post.title}}]({{ post.url | relative_url }})
{% endfor %}
