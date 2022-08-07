---
layout: about
description: >
  A boutique Jekyll theme for hackers, nerds, and academics,
  with a focus on personal sites that are meant to impress.
hide_description: true
tags:       [example]
grouped: true
---

<!-- 大类 -->
{% for item in site.featured_categories %}
  <h2>
    <a href="{{ item.url }}">
      {{ item.title }}
    </a>
  </h2>
{% endfor %}
<!-- 标签类 -->
{% for item in site.featured_tags %}
  <h2>
    <a href="{{ item.url }}">
      {{ item.title }}
    </a>
  </h2>
{% endfor %}