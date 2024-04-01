---
title: "Internal R packages for Open Science in Agrometeorology"
subtitle: "Regular Talk"
excerpt: "Persentation of the Agromet and SIGA packages developed by INTA"
date: 2022-02-05
date_end: "2022-02-05"
author: "Yanina Bellini Saibene"
location: "Online (Europe)"
event: "FOSDEM'22"
event_url: https://fosdem.org/2022/
draft: false
# layout options: single, single-sidebar
layout: single
categories:
- Regular Talk
- RSE
- English
- R
tags:
- RSE
- R
- packages
- Agromet
links:
- icon: images
  icon_pack: fas
  name: slides 
  url: https://docs.google.com/presentation/d/1sSZ2IzM2OBAQZUYTZ7phEYbrUzGTzvuob88hVtF-5uk/edit?usp=sharing
- icon: youtube
  icon_pack: fab
  name: video (talk and Q&A)
  url: https://ftp.osuosl.org/pub/fosdem/2022/D.research/open_research_agrometeorology.webm
- icon: github
  icon_pack: fab
  name: code Agromet
  url: https://github.com/AgRoMeteorologiaINTA/agromet  
- icon: github
  icon_pack: fab
  name: code SIGA
  url: https://github.com/AgRoMeteorologiaINTA/siga  
  
---

Argentina's National Institute of Agricultural Technology (INTA) conducts research and development for the agricultural sector. Environmental conditions influence agricultural activity; in particular, climatic conditions have a favorable or detrimental effect on production. Thus, it is essential to monitor and analyze the different agro-meteorological variables to describe these conditions and their impact on agricultural and livestock production. With this approach, INTA has an extensive ground network of conventional and automatic weather stations. In addition, there is an information system (http://siga.inta.gob.ar) with predefined queries and visualization on this data for internal and external use. All the information generated by the institution is openly shared under a CC-BY-NC license. INTA is a decentralized institution and generates research, analysis, and reports at different scales (national to local). The processes to perform these tasks use various software tools and different methodologies. Moreover, these processes are in the computer and the head of the researchers.
Developing internal packages or libraries has great potential to promote reproducible analysis frameworks, improve an organization's code quality, enhance knowledge management (Riederer, 2021), standardize and make processes transparent, and open software and data to society.

The {agromet} package includes a series of functions that can be used regularly for the calculation of agrometeorological indices and statistics. The input meteorological data works under the tidy data philosophy, so the package functions are generic. They can be applied to any tabular dataset regardless of its origin, order, or column names. However, according to INTA's internal requirements, the package also incorporates tools to read data in an INTA format. This package has implemented functions for calculating indexes and variables of agricultural interest, standardizing how these computations are made. It also incorporates mapping functions with scale and reports templates.

The package {siga} downloads and reads data from INTA's Agrometeorological Information and Management System programmatically.

This talk will discuss the decision process to generate a series of internal packages designed to be used by INTA users but with enough generality to be helpful to a broad community. Their development, current use, and this experience encouraged the generation of similar packages for soil data.

Organization on GitHub: https://github.com/AgRoMeteorologiaINTA
