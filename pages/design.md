---
layout: page
show_meta: false
title: "Style your content!"
subheadline: "Layouts of Huuzkee"
header:
   image_fullwidth: "aaa-wide-01.jpg"
permalink: "/design/"
---
<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>