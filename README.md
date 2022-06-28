[![Build Status](https://travis-ci.com/mskilab/fishHook.svg?branch=master)](https://travis-ci.com/mskilab/fishHook)
[![codecov.io](https://img.shields.io/codecov/c/github/mskilab/fishHook.svg)](https://codecov.io/github/mskilab/fishHook?branch=master)


<img src="images/fishhook.png" width = "500">

fishHook
======

R package for applying Gamma-Poisson regression to identify statistical
enrichment or depletion of somatic mutations in arbitrary (sets of) genomic
intervals after correcting for genomic  covariates, e.g. replication timing,
sequence context, chromatin state.

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)

<div id="installation"/>

Installation 
-----------

1. Install devtools from CRAN (if you don't have it already)

  ```
  install.packages('devtools')
  ```

2. Install gUtils 

  ```
  devtools::install_github('mskilab/gUtils')
  ````

3. Install fishHook

  ```
  devtools::install_github('mskilab/fishHook')
  ````


<p align="center">
<img src="images/qqdreams.jpg" width = "700">
</p>

<div id="rdocs"/>

Documentation 
------------

[fishHook Tutorial](http://mskilab.com/fishHook/tutorial.html)

[fishHook Developer Reference](docs/reference.md)

<!--

[R Documentation](https://raw.githubusercontent.com/mskilab/fishHook/marcin/fishHook.pdf)

-->

<div id="attributions"/>

Attributions
------------
> Marcin Imielinski - Assistant Professor, Weill-Cornell Medical College. Core Member, New York Genome Center.

> Zoran Gajic - Undergraduate Research Assistant, Rutgers University, Weill Cornell Medicine, New York Genome Center.


