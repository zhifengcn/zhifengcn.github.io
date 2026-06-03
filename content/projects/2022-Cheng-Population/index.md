---
title: "When geostatistics meets machine learning: how do they compete and complement in dynamic population mapping?"
date: 2022-08-05
links:
  - name: Paper - IJGIS
    url: https://www.tandfonline.com/doi/full/10.1080/13658816.2020.1854767
  - name: Paper - TUDST
    url: https://journals.sagepub.com/doi/10.1177/27541231221114169
summary: Can geostatistical models or machine learning better capture population dynamics? Which performs better under different data availability? How can their strengths be integrated for more precise dynamic population modelling?
tags: ''
featured: true
---
This project was led by Zhifeng Cheng and Jianghao Wang.

**Abstract**
Fine-grained dynamic population data are instrumental in climate change response, resource allocation, and epidemic control. With the increasing availability of high-frequency human digital footprint data, the past decades have witnessed numerous efforts in mapping populations at fine spatiotemporal scales. Two methodological families dominate this space: spatial statistical models grounded in geostatistics, which explicitly encode spatiotemporal dependency, and machine learning techniques, which flexibly leverage rich auxiliary covariates. However, the field still lacks a unified standard in modelling strategy and auxiliary data selection, particularly a systematic comparison between newly developed machine learning techniques and traditional spatial statistical methods under different covariate provisions.

This project addresses both gaps. In a case study of hourly population mapping at 100-m resolution in Beijing, we benchmarked two spatial statistical models, the Bayesian space-time model and geographically and temporally weighted regression, against two machine learning techniques, random forest and eXtreme gradient boosting. The Bayesian space-time model in conjunction with urban function data achieved the best performance, underscoring the value of spatiotemporal dependency information and urban function covariates in fine-scale population mapping. Building on these insights, we constructed a hybrid downscaling model that integrates random forest with area-to-point kriging, and applied it to time-series mobile phone positioning data to produce monthly 1-km gridded population distributions across China in 2015. The estimated products capture inner-annual population variations, especially during periods of large-scale population movement such as festivals, holidays, and short-term labour flows, and exhibit higher consistency with census data than popular global population products. Together, the hourly Beijing maps and the monthly nationwide China dataset are released to the research community as a credible foundation for population-dependent decisions.

<!--more-->
