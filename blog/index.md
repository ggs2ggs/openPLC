---
layout: inset
title: Blog
---

## Archived Website
The information on this website is outdated. It is kept in here for historical purposes only. Please refer to [https://autonomylogic.com](https://autonomylogic.com) for the most up to date information about the OpenPLC Project.

<ul style="list-style-type: none;">
  {% for post in site.posts %}
    <li>
      <h2 class="posts__article_title"><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
