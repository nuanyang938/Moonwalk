---
layout: abc
title: About
---

<style type="text/css" media="screen">
    .container {
      margin: 1em auto;
      max-width: 60em;
      text-align: center;
    }
    h1 {
      margin: 30px 0;
      font-size: 1em;
      line-height: 1;
      letter-spacing: -1px;
    }
  </style>
  
  <div class="container">
    <a href="{{ "/" | relative_url }}">{{ site.theme_config.back_home_text }}</a>
    <h1 class="post-title">{{ page.title }}</h1>
  </div>
{% include date_and_social_share.html %}
{{ content }}
