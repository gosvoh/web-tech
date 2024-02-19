---
layout: page
title: "Веб-технологии gosvoh"
is_home: true
---

# Веб-технологии 2023 - Проектирование и анализ языков веб-решений

{% for page in site.pages %}
{% if page.is_home %}
{% continue %}
{% endif %}
[{{ page.title }}]({{ page.url | relative_url }})
{% endfor %}
