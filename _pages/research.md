---
layout: research
permalink: /research/
title: Research
description:
years: [2020, 2019, 2018]
---

### Interests
My research lies in the field of Computer Vision and Deep Learning. For now I focus on the subspace learning and clustering, which can be unified to the framework of Representation Learning.

### Publications
Publications by categories in reversed chronological order.

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
