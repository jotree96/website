---
layout: default
title: Jonathan Baum, M.Sc.
---

# YAB - Yet another blog
> Informationswissenschaft, Methoden des Natural Language Processing, Daten- und Informationskompetenz, Linux, ..und viele weitere Themen sind in meinem Interesse.
Hier findest du meine neuesten Beiträge:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>  
      <small>({{ post.date | date: "%d.%m.%Y" }})</small>
    </li>
  {% endfor %}
</ul>
