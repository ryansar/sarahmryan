---
abstract: <h3>Rationale and Objectives</h3><p>A standard lung template could improve population-level analyses for computed tomography (CT) scans of the lung. We develop a fully automated preprocessing pipeline for image analysis of the lungs using updated methodologies and R software that results in the creation of a standard lung template. We apply this pipeline to CT scans from a sarcoidosis population, exploring the influence of registration on radiomic analyses.</p><h3>Materials and Methods</h3><p>Using 65 high-resolution CT scans from healthy adults, we create a standard lung template by segmenting the left and right lungs, nonlinearly registering lung masks to an initial template mask, and using an unbiased, iterative procedure to converge to a standard lung shape (Dice similarity coefficient ≥0.99). We compare three-dimensional radiomic features between control and sarcoidosis patients, before and after registration to a study-specific lung template.</p><h3>Results</h3><p>The final lung template had a right lung volume of 2967 cm<sup>3</sup> and left lung volume of 2623 cm<sup>3</sup>, with a median HU = −862. Registration significantly affected radiomic features, shifting the HU distribution to the left, decreasing variability, and increasing smoothness (<i>p</i> < 0.0001). The registration improved detective ability of radiomics; for contrast, autocorrelation, energy, and homogeneity, the group effect was significant postregistration (<i>p</i> < 0.05), but was not significant preregistration.</p><h3>Conclusion</h3><p>The final lung template and software used for its creation are publicly available via the <i>lungct</i> R package to facilitate its use in practice. This study advances lung imaging by developing tools to improve population-level analyses for various lung diseases.</p>
authors:
- admin
- Brian Vestal
- Lisa A Maier
- Nichole E Carlson
- John Muschelli
date: "2019-12-13"
doi: "10.1016/j.acra.2019.10.030"
featured: true
image:
  caption: ''
  focal_point: Right
projects: []
publication: 'Academic Radiology'
publication_short: ""
publication_types:
- "2"
publishDate: "2019-12-13"
slides: ""
summary: A standard lung template could improve population-level analyses for computed tomography (CT) scans of the lung. We develop a fully automated preprocessing pipeline for image analysis of the lungs using updated methodologies and R software that results in the creation of a standard lung template. We apply this pipeline to CT scans from a sarcoidosis population, exploring the influence of registration on radiomic analyses
tags:
- Source Themes
title: Template Creation for High-Resolution Computed Tomography Scans of the Lung in R Software
url_code: ""
url_dataset: ""
url_pdf: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
![template creation](/img/template.jpg)
