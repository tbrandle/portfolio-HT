---
layout: page
title: About
permalink: /about/
---

{% for project in site.projects %}
  <h2>    
    {{ project.title }}
  </h2>
{% endfor %}
