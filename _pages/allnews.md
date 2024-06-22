---
title: "News"
layout: textlay
excerpt: "Allan Lab at Leiden University."
sitemap: false
permalink: /allnews.html
---

<p>&nbsp;</p>

## News

{% for article in site.data.news %}
<p>{{ article.date }} <br> {{ article.headline | markdownify}}</p>
{% endfor %}
