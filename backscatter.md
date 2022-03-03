---
layout: page
title: backscatter
---



{% for post in site.posts %}   
    <a href="{{ post.url }}">{{ post.title }}</a>
    <small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} . <a href="http://mypage.github.com{{ post.url }}#disqus_thread"></a></small>         
{% endfor %} 

