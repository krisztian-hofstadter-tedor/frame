---
title: tEdör aka Krisztián Hofstädter
layout: default
---
Hello, this is a framework for a jekyll website by [k](https://khofstadter.info/assets/doc/K-Hofstader-CV-general-2019.pdf).

![](../assets/images/2019-03-03-multilingual-website-workshop-02.jpg)

<h2>Blog posts:</h2>

  <ul>
    {%- for post in site.posts -%}
    <li>
      <h3>
        <a href="{{ post.url | relative_url }}">
          {{ post.title | escape }}
        </a>
      </h3>
    </li>
    {%- endfor -%}
  </ul>
