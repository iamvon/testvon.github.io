---
layout: archive
title: "Toán lý thuyết"
permalink: /theory/
author_profile: true
---

{% include base_path %}

{% for post in site.theory reversed %}
  {% include archive-single.html %}
{% endfor %}
