---
layout: page
title: Tags
permalink: /tags/
---

<div class="tags">
    {% for tag in site.tags %}
    <a href="/t/{{ tag[0] }}">{{tag[0]}}</a>
    {% endfor %}
</div>
