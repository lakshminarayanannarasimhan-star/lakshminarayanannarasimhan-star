
---
layout: default
title: Strategic Technology Initiative
---

<section class="hero">

<h1>
Strategic intelligence for technology systems, infrastructure, and industry evolution.
</h1>

<p>
Independent consulting and think tank providing architecture expertise and strategic insight.
</p>

</section>

<section class="section">
<h2>Latest insights</h2>
<div class="article-list">
{% for post in site.posts %}
<a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
</div>
</section>
