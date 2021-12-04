# Prediction of drag and lift coefficients of NACA airfoils
Motivation for this project is to help the engineers predict the 'Drag coefficient' and 'Lift coefficient' of their NACA 4 digit airfoils without running a physical test or a CFD simulation

![Attriutes of airfoil](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Wing_profile_nomenclature.svg/500px-Wing_profile_nomenclature.svg.png)

**Input variables:**
* Angle of attack
* Maximum thickness of the airfoil
* Chord at maximum thickness
* Maximum camber of the airfoil
* Chord at maximum thickness
* Reynolds number

**Target variables**
* Lift coefficient
* Drag coefficient

**Data source**
Airfoil data is obtained from airfoiltools website by web scraping
[Data source](http://airfoiltools.com/search/index?m%5Bgrp%5D=naca4d&m%5Bsort%5D=1)