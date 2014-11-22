---
title: latest
permalink: /another/
layout: archive
image: p-cal-3.png
---
This is a second page.

These are my latest posts:

<div class="tiles">
{% for post in site.posts %}
    {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->