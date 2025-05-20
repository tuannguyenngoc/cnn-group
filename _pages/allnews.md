---
title: "News"
layout: textlay
excerpt: "CNN group at UoM."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<strong>{{ article.date }}<strong><br>
{{ article.headline | markdownify}}
{% endfor %}
