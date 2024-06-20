---
title: Azure AI Document Intelligence Exercises
permalink: index.html
layout: home
---

# Azure AI Document Intelligence Exercises

The following exercises are designed to support the modules on Microsoft Learn.


{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Exercises'" %}
{% for activity in labs  %}
- [{{ activity.lab.title }}]({{ site.github.url }}{{ activity.url }})
{% endfor %}
