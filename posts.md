---
layout: default
title: "Blog"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}

**Random**
* [Networking] This cute [cartoon](https://jvns.ca/networking-zine.pdf) summarizes extremely well some important network protocols such as DNS, HTTP, UDP, TLS.
