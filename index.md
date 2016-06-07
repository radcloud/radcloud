---
layout: default
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

<div class="blog-index">  
  {% assign post = site.posts.first %}
  {% assign content = post.content %}
  {% include post_detail.html %}
</div>
