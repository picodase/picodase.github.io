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
* Left a Ph.D in Biochemistry, University of Washington, 2025
* H.B.S. in Biochemistry and Biophysics, Oregon State University, 2021

Work experience
======
* 2022-2025: Research Assistant 
  * Institution: University of Washington, Institute for Protein Design (IPD)
  * Project: Automated refinement of asymmetric protein domains into single-particle cryo-EM maps
  * Supervisor: Prof. Frank DiMaio
  
* 2020-2021: Research Assistant 
  * Institution: Oregon State University
  * Project: A taxonomy of computational biomolecular features
  * Supervisor: Prof. Victor Hsu

Skills
======
* Spatial deep learning
  * SE(3)-invariant models
  * Diffusion
  * Autoencoders
* Representation design
* Protein structure modeling
* RoseTTAFold3 (modelforge)

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
* Co-created and co-administered the Biochemistry Undergraduate Reading Program
