---
title: Home
layout: home
nav_order: 1
---
# Introduction to AI and Programming
{: .no_toc }
ROB 102, Fall 2024 at the University of Michigan
{: .fs-6 .fw-300 }

This is the course page for the Fall 2024 offering of [Hello, Robot! Introduction to AI and Programming](https://hellorob.org){:target="_blank"} at the University of Michigan. This site contains information relevant to Michigan students.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

# Meeting Times

<i class="fa-solid fa-chalkboard-user"></i> **Lectures:** 

- M 1:30 - 3:00, 1050 FRB
- W 1:30 - 3:00, 1050 FRB

<i class="fa-solid fa-flask"></i> **Labs:**

- F 12:30 - 2:30, 1050 FRB

# Instructors

<div class="staff-row">
{% assign instructors = site.staff | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
</div>

# Graduate Instructor

<div class="staff-row">
{% assign gsis = site.staff | where: 'role', 'Graduate Student Instructor' %}
{% for staffer in gsis %}
{{ staffer }}
{% endfor %}
</div>

{% assign teaching_assistants = site.staff | where: 'role', 'Instructional Aide' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

# Instructional Aides

<div class="staff-row">
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
</div>
{% endif %}

# Office Hours

Office hours will be held in **FRB 2000** and on **Zoom**.

The schedule can be found below.

<iframe src="https://calendar.google.com/calendar/embed?src=c_caa9ab242d12888c45dd8da82a746fed62e64a281e2ec5430e1732447ff2977d%40group.calendar.google.com&ctz=America%2FNew_York" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>
