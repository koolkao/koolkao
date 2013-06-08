---
layout: page
title: WNL Reason
tagline: New GitHub blog
---

I am a PhD statistician and pain physician at Stanford. My interests are machine learning, omics, item response theory,wellness, and healthcare delivery. 

<h2>Some basic info</h2>
<ul>
  <li><a href="https://dl.dropbox.com/u/4166373/CV/Ming-Chih-Kao-CV.pdf">Curriculum Vitae</a></li>
  <li><a href="https://plus.google.com/100952468373748554033/about">Google+</a></li>
  <li><a href="http://www.linkedin.com/profile/view?id=386626">LinkedIn</a></li>
</ul>

<h2>Recent blog posts</h2>
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

