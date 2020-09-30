---
layout: archive
permalink: /
title: "O que temos"
image: 
  feature: dog-header.jpg
---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
