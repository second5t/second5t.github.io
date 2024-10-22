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
* Pursuing Ph.D in Computer Science, University of Colorado, Boulder, 2030 (expected)
* B.S. in Information Security, Huazhong University of Science and Technology, 2023

Work experience
======
* 2023.12 - 2024.8
  * University of Colorado, Boulder
  * Visiting Scholar

* 2021.7 - 2022.8
  * Singularity Security Lab
  * Intern Security Researcher: Windows User Service logical vulnerability research, Fuchsia OS security architecture analysis and vulnerability discovery

* 2021.1 - 2021.2
  * Tencent Security Xuanwu Lab
  * Intern Security Researcher: Windows Defender Engine analysis and in-wild vulnerabilities analysis
  
Skills
======
* Programming Language
  * ASM, C, C++, Python, Golang
* CTF
  * Reverse Engineering, Pwn
* Windows Security Research
* Exploitation Development

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
* ACM CCS 2023 Artifact Evaluation Committee
* Team Leader of L3H_Sec CTF Team in 2022

Awards
======
* Member of team 42-b3yond-6ug winning AIxCC semi-final
* Member of team 42-b3yond-6ug winning AIxCC Small Business Track
* Outstanding graduate from CSE College of Huazhong University of Science and Technology (HUST)
* No. 8 of ByteCTF2022
* 2022 Science and Technology innovation scholarship of HUST
* No. 2 of DEFCON30 CTF FINAL with Katzebin
* Black Hat Asia & USA, Student Scholarship, 2022
* No. 5 of *CTF2022
* 2021 Science and Technology innovation scholarship of HUST
* 2020 Science and Technology innovation scholarship of HUST
* Second Prize of National College Student Information Security Contest Innovation Practice Ability Competition 2020
* No. 4 of WCTF2020
* No. 2 of SCTF2020
* No. 11 of the First National Middle School Students’ Cybersecurity Competition 2018
* No. 9 of the First Middle School Students’ Cybersecurity Cup hosted by Beijing University of Posts and
* Telecommunications 2018
* First Prize of National Olympiad in Informatics in Provinces (NOIP) 2017 Liaoning

CVE and Bugs
======
* [\[PATCH\] drivers: clocksource: fix memory leak in davinci_timer_register](https://lore.kernel.org/lkml/20230322151945.102353-1-flno@hust.edu.cn/)
* [CVE-2022-21895](https://msrc.microsoft.com/update-guide/en-US/advisory/CVE-2022-21895): Windows User Profile Service Elevation of Privilege Vulnerability