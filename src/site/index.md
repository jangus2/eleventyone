---
title: JasonAng.us
subtitle: Research Interests
layout: layouts/base.njk
---


## Research Focus

- Personality
- Religious Coping
- Forgiveness
- Marriage and Family

## Marriage and Family
- Certified PREPARE/ENRICH Facilitator


## Post pages


<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>
