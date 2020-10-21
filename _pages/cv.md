---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
[Download cv here](http://teresa-canasbajo.github.io/files/Teresa_CV_2020_v3.pdf)
{% include base_path %}

Education
======
* B.S. in Psychology, Universidad Autonoma de Madrid (Spain), 2011 - 2015
* M.S. in Psychological Research, University of Edinburgh (UK), 2015 - 2016
* Ph.D in Vision Science, University of California, Berkeley, 2017 - Present (expected graduation date: Spring 2022)

Work experience
======
* Berkeley Deep Drive Project Lead.
  * University of California, Berkeley
  * Project: Investigating driver’s attention while monitoring an autonomous vehicle.
  * Duties included: 
      • This project investigates whether drivers can monitor efficiently the actions of an automated car. To this purpose, we analyze drivers gaze and
      attention maps in a driving simulator in different degrees of car automation, from fully manual to fully autonomous vehicle.
      • Manage a team of four people (two research assistants, one human factor expert and an engineer) and coordinate tasks that involve the development
      of driving simulator scenarios and the development of code to analysis driving behavior and eye movements.
      • Built a Python API to record, analyze, classify and describe drivers’ eye movements while driving a manual, semi‑autonomous or fully autonomous
      vehicle using Pupil Labs mobile eye‑tracker. This code includes processing and segmentation of a egocentric‑viewpoint video feed
      that captures drivers perception of the driving environment. Open‑sourced on Github.
      • Applied a Adaptive Whitening Saliency model and top‑down driving models (such as the vanishing point model) to predict areas of the driving
      simulation that will most likely attract the driver’s attention. In the near future, we will use these metrics to detect driver attention lapses, as a
      part of a driver‑monitoring system.
      • Applied an object‑detection pre‑trained model from TensorflowHub specialized for multiple object localization on single images to detect and
      classify driving‑relevant (traffic signs, cars, pedestrians) and driving‑irrelevant (billboards, trees, off‑road pedestrians) in drivers’ egocentric  
      viewpoint
      video. The purpose of this object‑detection approach is to be able to determine whether drivers’ eye‑movements land on each of these
      objects and areas.
      • Built a simulated city using Prescan, Simulink and Matlab for a Force Dynamics driving simulator. Our code allows simultaneous collection of
      driver behavior.

* Vision Science Graduate Student Researcher
  * University of California, Berkeley
  * Project: Individual Differences in Holistic Processing of Faces.
  * Duties included:
      • The aim of my thesis project is to use a combination of behavioral and eye‑tracking methods to understand how experience may shape the way
      each person perceives the faces around them.
      • Used statistical analysis software in Python, R and Matlab to program experiments and statistical analysis for behavioral data. Used visualization
      tools such as Matplotlib and Seaborn to help interpret the data.
      • Collected human data and developed and tested regression and analysis of variance models to predict face perception abilities to show how
      face perception depends on the unique experience of each person. Applied bootstrap and permutation methods to test the significance of
      resulting effects.
      • Applied image‑similarity measures such as normalized pixel‑wise crosscorrelation, structural similarity index and clustering to compute similarity
      between faces human perceive in the world. Used feature map extraction and gram‑matrix style transfer strategies from the Convolutional
      Neural Networks field to develop a face‑space for higher‑level face similarity.
  
Skills
======
Programming Languages: Python, MATLAB, SQL, R
Frameworks and Tools: OpenCV, Git, NumPy, Pandas, scikit‑learn, Bash, Tensorflow, Unix Systems

Awards
======
2019 - Campus Outstanding Graduate Student Instructor Award, University of California, Berkeley
2017 - Fulbright scholarship for doctorate programs, U.S ‑ Spain Fulbright Commission
2015 - “La Caixa” Fellowship for Postgraduate Studies Abroad, Fundacion La Caixa
2015 - Undergraduate Thesis Distinction, Facultad de Psicologia, Universidad Autonoma de Madrid Madrid, Spain

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Volunteering at Bay Area Scientists in Schools.
* Mentored 8 undergraduate research assistants. 
