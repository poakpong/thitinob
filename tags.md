---
layout: page
title: แท็กทั้งหมด
permalink: /tags/
---

<div class="tag-index">
  {% for item in site.data.tag_slugs %}
    <a class="tag-pill" href="{{ '/tag/' | append: item.slug | relative_url }}">{{ item.name }}</a>
  {% endfor %}
</div>
