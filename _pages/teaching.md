---
layout: page
permalink: /teaching/ #if i remove this, you cant find the site in general (sopgri.github.io/teaching)
title: teaching
description: Course materials, schedules, and resources for classes taught.
nav: false #if false then it doesn't show in the nav bar
nav_order: 6 #position in the nav bar
calendar: true
---

This page displays a collection of courses with detailed schedules, materials, and resources. You can organize your courses by years, terms, or topics.

{% include calendar.liquid calendar_id='test@gmail.com' timezone='Asia/Shanghai' %}

{% include courses.liquid %}
