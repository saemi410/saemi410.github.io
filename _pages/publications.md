---
layout: page
permalink: /publications/
title: publications
description: publications by categories in reversed chronological order. 
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<h2>Conference Proceedings</h2>
{% bibliography -f {{ site.scholar.bibliography }} -q @*[conference=true]* %}

<h2>Workshop Papers</h2>
{% bibliography -f {{ site.scholar.bibliography }} -q @*[workshop=true]* %}

</div>
