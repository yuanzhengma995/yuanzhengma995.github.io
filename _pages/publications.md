---
layout: archive
title: "Research"
permalink: /publications/
author_profile: True
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}


<!--
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->

{% for index, post in site.publications reversed %}
{{ index }}. {% include archive-single.html %}
{% endfor %}
