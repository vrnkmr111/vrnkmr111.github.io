---
title: welcome to jekyll
layout: post
date:   2019-10-10 17:34:24 +0530
comments: true
categories:
- AWS
- VPC
- VPC-Peering
author: K varun Kumar
---

<h1>{{ page.author }}</h1>

{% for category in page.categories %}
		<span class="tag">#{{category}}</span>
{% endfor %}
