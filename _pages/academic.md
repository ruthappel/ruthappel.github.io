---
layout: page
permalink: /academic-writing/
title: Academic Writing
nav: true
nav_order: 1
---

<div class="publications">
  <!-- All Published Academic Work (grouped by type and year) -->
  {% bibliography -f {{ site.scholar.bibliography }} -q @under_review,@work_in_progress, @article,@incollection,@inproceedings,@workshop %}
</div>