---
title: Writing system
layout: index
---

{% for exhibit in site.exhibits %}

<img src="{{ exhibit.image-url }}" width = 256>
<p>{{ exhibit.title }}</p>
<p>Script type: {{ exhibit.Script-type }}</p>
<p>Time-period: {{ exhibit.Time-period }}</p>
<p>Direction: {{ exhibit.Direction }}</p>
<p>Languages: {{ exhibit.Languages }}</p>
<p>image-url: <a href="{{ exhibit.image-url }}">{{ exhibit.image-url }}</a></p>

{% endfor %}