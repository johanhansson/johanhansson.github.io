---
layout: default
title: Axel Hansson
images:
  - 31bf173f-de67-45d0-b235-4c94ffb4b9e9.jfif
  - 35065a67-974e-429b-8db2-a960ff45f315.jfif
  - 514150f3-50e2-404b-b675-998589e7b447.jfif
  - 723a231c-7c1b-4599-86a1-95211303b724.jfif
  - a6e7c9b1-fcee-495c-8a42-345b74b1b5a5.jfif
  - dc367c16-058b-481d-b7af-a5a7681ba052.jfif
---

<div class="gallery">
{% for img in page.images %}
  <img src="{{ '/assets/images/' | append: img | relative_url }}" alt="{{ img }}">
{% endfor %}
</div>
