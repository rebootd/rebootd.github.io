---
layout: page
title: Software bits
tagline: and other musings
---
{% include JB/setup %}

    
## Please note

This is the beginned of a definitely NOT comprehensive archive of articles, facts, and talk materials. The business site is found <a href="http://computerist.co">here</a>.


## Latest hits

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


## To-Do

I'll be adding moire articles, and perhaps re-publishing old ones, as time permits.

