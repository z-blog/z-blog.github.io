---
layout: page
title: Lisp View
permalink: /list/
---

 <ul class="chaos">
  {% for post in site.posts %}
  <li><a  title="{{ post.title }}" class="title" href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>  <span class="time"> {{ post.date | date_to_string }} </span>   </li>
  {% endfor %}
 </ul>
