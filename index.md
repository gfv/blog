---
title: Botan Investments
layout: page
---
{% for post in site.posts %}
<div class="c-post__header">{{ post.date | date: "%b %-d, %Y" }} <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></div>
{{ post.content }}
{% endfor %}

<p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>
