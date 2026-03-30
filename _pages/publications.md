---
layout: page
permalink: /research/
title: research
description:
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<div class="publications">

<h2>Working Papers</h2>

{% bibliography --query @unpublished[note!~Work in Progress] %}

<h2>Work in Progress</h2>

{% bibliography --query @unpublished[note=Work in Progress] %}

</div>
