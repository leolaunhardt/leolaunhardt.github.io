---
layout: page
permalink: /blog/
title: Blog
description: Notes on applications, scholarships and life as a student.
nav: true
nav_order: 5
---

<!-- _pages/blog.md -->

<div class="row row-cols-1 row-cols-md-2">
  {% for post in site.posts %}
    <div class="col mb-4">
      <a href="{{ post.url | relative_url }}" style="text-decoration: none;">
        <div class="card h-100 hoverable">
          {% if post.thumbnail %}
            <img src="{{ post.thumbnail | relative_url }}" class="card-img-top" alt="{{ post.title }}">
          {% endif %}
          <div class="card-body">
            <h3 class="card-title" style="font-size: 1.25rem;">{{ post.title }}</h3>
            <p class="card-text">{{ post.description }}</p>
            <p class="card-text">
              <small class="text-muted">{{ post.date | date: "%B %Y" }}</small>
            </p>
          </div>
        </div>
      </a>
    </div>
  {% endfor %}
</div>
