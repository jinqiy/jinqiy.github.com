---
layout: page
title: Have a good day!
tagline: Keep hungry, and KISS.
---
{% include JB/setup %}

Hello, here is my first blog powered by Jekyll Bootstrap.
There are lots of things to be recorded here soon.
Now, while you are watching this page, I am busy on filling the site.
Or you can check out my older blogs on [CSDN] (http://my.csdn.net/jackyyen).

Yes, I am not yet familiar with Jekyll and Github. So, here below is some link for refer to.
## FYI

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

##Posts list

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

Create the first page for this blog...

