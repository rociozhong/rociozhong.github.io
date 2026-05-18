---
layout: page
permalink: /publications/
title: Research
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<h2 class="year">Publications</h2>
{% bibliography -f papers -q @*[abbr!=Under Review, abbr!=In Progress] %}

<h2 class="year">Under Review</h2>
{% bibliography -f papers -q @*[abbr=Under Review] %}


</div>
