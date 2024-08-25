---
layout: default
title: atemporal
permalink: /atemporal/
description:
nav: true
nav_order: 3
---
### **ATEMPORAL: Algebraic and Tensor Methods for Polarimetric Phase Retrieval**

<div style="display: flex; justify-content: space-between; align-items: center;">

  <div style="width: 78%;">
    {% capture markdown_content %}
**PI:** Julien Flamant <br/>
**Duration:** 2024 - 2027 <br/>
**Budget:** 291 k€ <br/>
**Funding:** ANR JCJC grant number ANR-23-CE48-0007
    {% endcapture %}

    {{ markdown_content | markdownify }}
  </div>

  <div style="width: 20%;">
    <img src="/assets/logo/anr.jpg" alt="anr logo" height=50px width="auto">
  </div>

</div>


#### Context and project summary
Polarimetric phase retrieval is an emerging class of phase retrieval problems, which arise when considering light polarization in coherent diffractive imaging applications.
Polarization permits to account for the vector nature of light-matter interaction: as such, polarimetric imaging enables to decipher unique features (e.g., anisotropy) that are inaccessible to conventional imaging.

<p align="center">
  <img src="/assets/img/fig_illustration_Atemporal.png" alt="illustration atemporal" height=300px>
</p>

Recently, in {% cite flamant2024polarimetric %} we demonstrated that 1D polarimetric phase retrieval (PPR) can be formulated and efficiently solved as a greatest common divisor (GCD) problem between measurement polynomials.
This equivalence, specific to PPR, allows the use of algebraic reconstruction methods based on approximate GCD computations through numerical linear algebra.
However, the performance of existing approaches is insufficient with respect to realistic optical imaging settings: this includes  large dimensionality of the data and poor experimental signal-to-noise ratio encountered in practice.
The ATEMPORAL project aims at filling this gap by developing a complete algebraic framework for solving phase retrieval problems arising in polarimetric CDI imaging.
To this end, ATEMPORAL will introduce new, robust to noise algebraic approaches by taking advantage of prior information about the solution. These results will be first established for the 1D case before being extended to the 2D case by exploiting the natural tensor representation of polarized images.
The relevance of the methodological tools developed in the project will be demonstrated experimentally on several reference scenarios for polarimetric CDI imaging.



#### **Collaborators**
Marc Allain (Institut Fresnel, Aix-Marseille Univ.), David Brie (CRAN, Univ. Lorraine), Marianne Clausel (IECL, Univ. Lorraine), Virginie Chamard (Institut Fresnel, CNRS), Patrick Ferrand (Institut Fresnel, Aix-Marseille Univ.), Konstantin Usevich (CRAN, CNRS).
#### **Jobs**
For any of the positions below, contact me directly by [email](mailto:julien.flamant@cnrs.fr), joining a CV and a brief statement of interest.

- 6 month master's internship with possible Ph.D. continuation
- [24 month postdoctoral research fellow position](../assets/jobs/postdocOfferAtemporal2024.pdf), with [Konstantin Usevich](http://w3.cran.univ-lorraine.fr/perso/konstantin.usevich/) <span style="color:green"> [fulfilled] </span>

#### **Papers associated to the project**
{% reference flamant2024polarimetric %}
