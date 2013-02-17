---
layout: page
title: More Than A Developer
tagline: Tag line
---
{% include JB/setup %}


**Welcome to my blog!**
-----------------------

Be sure to check out the latest post or look in the archive to see if something else
interests you.

<br />

Latest Post
===========

<div class="latest_post">
    <span>{{ site.posts.first.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ site.posts.first.url }}">{{ site.posts.first.title }}</a>
</div>

<br />
<br />

<div id="aboutme">
  <a href="/pages/about.html">About the Author</a>
</div>


