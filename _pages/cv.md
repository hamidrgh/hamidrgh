---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in [Your Field], University of Padova, [Year] (expected/in progress)
* M.S./M.Sc. in [Your Field], [University Name], [Year]
* B.S./B.Sc. in [Your Field], [University Name], [Year]

Work experience
======
* [Start Date] - [End Date]: [Position Title]
  * [Institution/Company Name]
  * Duties included: [Description of responsibilities and achievements]
  * Supervisor: [Supervisor Name]

* [Start Date] - [End Date]: [Position Title]
  * [Institution/Company Name]
  * Duties included: [Description of responsibilities and achievements]
  * Supervisor: [Supervisor Name]
  
Skills
======
* [Technical Skill 1] (e.g., Python, Machine Learning, Data Analysis)
* [Technical Skill 2]
  * [Sub-skill or specific application]
  * [Sub-skill or specific application]
* [Language Skills] (e.g., English (Fluent), Italian (Native))

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* [Add any service activities, committee memberships, leadership roles, etc.]
* [Example: Reviewer for Journal Name]
* [Example: Member of Professional Organization]
