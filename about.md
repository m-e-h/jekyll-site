---
layout: page
title: About
permalink: /about/
---

Some information about you!

### More Information


        {% for guide in site.guides %}
1. [{{ guide.title }}](#guide{{ guide.id }} "{{ guide.title }}")
        {% endfor %}


A place to include any other types of information that you'd like to include about yourself.

### Contact me

[email@domain.com](mailto:email@domain.com)
