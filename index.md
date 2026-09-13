---
layout: default
title: Meu Blog
---

# Bem-vindo ao meu blog

Aqui compartilho notas sobre a minha visão limitada do mundo.

## Notas

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span class="post-meta">{{ post.date | date: "%d/%m/%Y" }}</span>
    </li>
  {% endfor %}
</ul>