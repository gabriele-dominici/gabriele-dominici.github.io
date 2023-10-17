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
* Ph.D in Explainable AI for Healthcare, Università della Svizzera Italiana, 2023 - Ongoing
  * Designing multimodal explainable Deep Learning models exploring causal models and counterfactuals.
* MPhil in Advanced Computer Science, University of Cambridge, 2022-2023
  * Grade: Distinction (highest grade possible)
* B.S. in IoT, Big Data & Web, Univestià degli studi di Udine, 2018-2021
  * Grade: 110/110 Cum Laude
  * The only student to complete it in two academic years rather than three

Work experience
======
* Research Intern @ MIT - Jul. 2023 - Aug. 2023
  * Selected among the 30 students to be part of SGI (Summer Geometric Initiative) organised by MIT.
  * Worked on [4 different research projects](https://summergeometry.org/sgi2023/) at the intersection between Geometric Processing and Deep Learning with mentors from MIT, Stanford and University of Toronto.
* Machine Learning Engineer @ Reply - Sep. 2021 - Sep. 2022
  * Spark and GCP were the main tools I used to build ML models when I worked as a consultant for one of the biggest telecom companies. 
  * Developed ML models to maximize revenue and subscription, reducing customer churn. We improved revenues by $\sim$20\%.
  * Completed the Databricks Certified Associate Developer for Apache Spark 3.0 course
* Research Assistant @ AILAB Università degli Studi di Udine - Jul. 2020 - Jun. 2021
  * Conducted a research project about the usage of Graph Neural Network for Fake News Classification. </br>
  I implemented a model similar to the SOTA on FEVER dataset and improved the previous results by $\sim$2\% the Accuracy on HOVER dataset. 
  * Analyzed data for a project about the retrieval of Adverse Drug Events related to Covid vaccines on Twitter. We also create a [website](http://ailab.uniud.it/covid-vaccines/).
  * Supervisor: Professor Giuseppe Serra, Dr. Enrico Santus
  
Projects
======
* [SHARCS: SHARed Concept Space for Explainable Multimodal Learning - MPhil Project](https://github.com/gabriele-dominici/SHARCS)
  * First solution to use concepts to explain multimodal models. It is able to explain one modality using the other and retrieve a missing modality.
  * It performs as well as non-interpretable baselines, providing explanations and substantially better performance on missing modality situations (an increase of up to $\sim$84\% accuracy)
* [Effect of Aggregation and Layers in GNNs on Concept Finding - GNNs Project](https://github.com/chengzu-li/L45-project)
  * Examined the effect of using different aggregators and GNNs on concept finding.
  * Proposed a new GNNs layer that used the similarity of the neighbourhood. It is theoretically more powerful than GCN and GAT and discovers better concepts.
* [ProtoWNet - Weight prediction with prototype similarity - XAI project](https://github.com/gabriele-dominici/R255_XAI_project)
  * Proposed a new version of ProtoPNet, that can discover a variable number of prototypes (taken from the train set) to solve the task.
  * It achieves comparable accuracy to the base model and better explanations (up to 5\% improvement) than other methods on Node Classification tasks.
* Different ways to approach NER with BERT - NLP Project
  * Developed and compared different approaches to use BERT in WNUT-17 shared task. Restructured the input of BERT to approach the problem as Text Classification rather than Token Classification.
  * Achieved an improvement of 2.5\% in the Macro F1 Score at word level.

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

Awards
======
* Best graduate student of the year of my degree course - Università degli Studi di Udine
* Scholarship given to top-3 student of the degree course - Università degli Studi di Udine
* Best Storytelling Award and Best Engagement Award @ MeshUp Reloaded - Friuli Innovazione
  
Summer Schools
======
* DeepMind - Mediterranean Machine Learning Summer School 2022
* DeepMind - Eastern European Machine Learning Summer School 2021

Extracurricular Activity
======
* Mentee and Ambassador @ LeadTheFuture
  * Selected as one of the ambassadors of LeadTheFuture to share its mission with Italian students.
  * Among the few Italian students selected to be mentees for LeadTheFuture, a leading mentorship non-profit organization for students in STEM, with an acceptance rate below 20\%.
