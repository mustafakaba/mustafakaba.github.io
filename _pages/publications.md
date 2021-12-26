---
layout: archive
title: ""
permalink: /research/
author_profile: true
---


## Publications

- Kaba, M. (2022). Who buys vote-buying? How, how much, and at what cost?. Journal of Economic Behavior & Organization, 193, 98-124.

[Link to Paper](https://www.sciencedirect.com/science/article/abs/pii/S0167268121004704){: .btn--research}



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
