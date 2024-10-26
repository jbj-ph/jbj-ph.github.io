---
layout: page
title: Recent Reading
permalink: /links/

---

Noticed around the web

<ul>
{% for item in site.pinboard.posts.tags.salty %}
  <li>
    <a href='{{ item.href }}'>{{ item.description }}</a> - {{ item.extended }}
  </li>
{% endfor %}
</ul>
