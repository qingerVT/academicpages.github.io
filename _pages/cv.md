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
* B.S. in Control Engineering, Tianjin University, 2009
* M.S. in Control Engineering, Tianjin University, 2012
* Ph.D in Computer Vision and Machine Learning, Virginia Tech, 2017

Work experience
======
* 2013-2017: Research Assistant
  * Research: 
    * Developing diverse models in solving structured prediction problems
    * Bidirectional image captioning (compared with BERT, we focus on bidirectional generation)
  * Supervisor: [Dhurv Batra](https://www.cc.gatech.edu/~dbatra/)

* 2016-2017: Research Intern
  * Institute of Deep Learning, Baidu Research
  * Research: meta-learning through natural language interaction
  * Supervisor: [Yi Yang](https://yangyi02.github.io/) and [Wei Xu](https://www.linkedin.com/in/emailweixu)

* 2012-2013: Research Assistant
  * Computational Bioinformatics and Bio-imaging Laboratory(CBIL)
  * Research: Genome/pathway-wide detection of interacting genomic/epigenetic loci and environment variables
  * Supervisor: [Yue Wang](https://ece.vt.edu/people/profile/ywang)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Serve as reviewers for NeruIPS, CVPR, ECCV and ICLR
