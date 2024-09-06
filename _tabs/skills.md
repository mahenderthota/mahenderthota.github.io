---
layout: page
icon: fas fa-archive
order: 2
title: My Skills
---


## Technical Skills
  <div class="skill-grid">
  {% for skill in site.data.skills %}
    <div class="skill-item">
      <img src="{{ skill.image | relative_url }}" alt="{{ skill.name }}" width="50" height="50">
      <h3>{{ skill.name }}</h3>
      <p>{{ skill.description }}</p>
    </div>
  {% endfor %}
