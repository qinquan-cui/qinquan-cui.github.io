---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

# Working Papers
The Role of Information Asymmetry Between Brand-Name and Generic Firms in Pharmaceutical Markets: Limit Pricing and the Generic Competition Paradox
Qinquan Cui, Kenan Arifoğlu and Dongyuan Zhan
Submitted
-- Listed in SSRN's top ten downloads.

# Journal Papers



<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
