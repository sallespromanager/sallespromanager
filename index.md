---
layout: page
title:
tagline: new ideas broght to a consistent production workflow
---
{% include JB/setup %}

business planning    [to see](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)
team building        [to be one](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)
product canvas       [strong concepts](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)
app reference design [better MVPs](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)
production workflow  [speed things up](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)
content creation     [not the same](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)
sw development       [the art](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




