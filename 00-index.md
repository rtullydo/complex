---
layout: page
title: "Complex Analysis Workshop"
permalink: "index.html"
---



Welcome to the (undergraduate) Complex Analysis Workshop, taught by me, [Ryan Tully-Doyle](https://rtullydo.github.io). This will be the permanent home of the files and videos I produce for the workshop. The associated text is William Johnson's [Calculus of Complex Functions](https://bookstore.ams.org/text-71).


  {% for post in site.posts %}
  <article>
    <h2>
      <a href="/math350/{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
    {{ post.content }}
  </article>
{% endfor %}
