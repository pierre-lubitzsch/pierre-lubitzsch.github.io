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
* Ph.D. in Computer Science, Technische Universität Berlin / BIFOLD, 2025 – present
  * Supervisors: Prof. Dr.-Ing. Sebastian Schelter (TU Berlin) and Prof. Dr. Maarten de Rijke (UvA)
  * Topic: Machine Unlearning for Recommender Systems
* M.Sc. in Computer Science, Freie Universität Berlin, 2021 – 2024
  * Thesis: *Neural Network Post-Filters for Video Coding* (in cooperation with Fraunhofer HHI)
* B.Sc. in Computer Science (grade 1.4), Freie Universität Berlin, 2018 – 2021
* Abitur (grade 1.7), Werner-von-Siemens-Gymnasium Berlin, 2012 – 2018
  * Advanced courses: Computer Science, Mathematics

Work Experience
======
* Feb 2025 – present: PhD Student
  * BIFOLD – Berlin Institute for the Foundations of Learning and Data / TU Berlin, Berlin, Germany
  * Research on Machine Unlearning for Recommender Systems
  * Supervisors: Sebastian Schelter and Maarten de Rijke

* Dec 2022 – Dec 2024: Student Assistant
  * Fraunhofer Heinrich Hertz Institute (HHI), Berlin, Germany
  * Work on neural network coding for video compression
  * Wrote master's thesis: *Neural Network Post-Filters for Video Coding*

* Aug 2020 – Oct 2020: Web Development Intern
  * writeaguide, Berlin, Germany
  * Fullstack web development internship

Skills
======
* Machine Learning & Deep Learning
  * PyTorch, scikit-learn
* Recommender Systems & Machine Unlearning
* Video Coding & Neural Network Post-Processing
* Programming: Python, C, C++
* Web Development: HTML, CSS, JavaScript (Fullstack)

Languages
======
* German (Native)
* English (Professional working proficiency)
* Spanish (Limited working proficiency)

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

Projects
======
* **Classification of reflective sentences** (Apr–Jul 2022)
  * NLP project within the PetraKIP research project at FU Berlin
  * Annotation and classification of sentences according to the cognitive Gibbs cycle using machine learning

* **Digit recognition neural net** (Dec 2019)
  * Neural network for digit classification trained on MNIST (~97.5% accuracy), written in Python

* **Joodle Dump** (Mar 2019)
  * Clone of *Doodle Jump* written in C using the SDL2 graphics library (group project, 6 members)

* **Mandelbrot Set** (Jul 2018)
  * Visualization of the Mandelbrot set in C++ using the SFML graphics library

* **Pong** (Nov–Dec 2017)
  * Clone of *Pong* written in Python
