---
layout: single
author: Beijie Zhang
title: Reviews
permalink: /reviews/
---

#### Here are some of my mock interviewer customer reviews. 

#### Click on a review to find out where they got the offers from.
<br>

<div>
    {% for review in site.reviews %}
        <a href="{{ site.url }}{{ review.url }}">{{ review.title }}</a>
        <div>{{ review.excerpt | markdownify }}</div>
    {% endfor %}
</div>
