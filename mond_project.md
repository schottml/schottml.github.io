---
layout: default
title: "MOND Project"
---

# MOND Project

---

**[View the Project on GitHub](https://github.com/wagoner47/mond_project)**

This project was done as a part of the PHYS 589 course "Tools in Theoretical Astrophysics" offered at the University of Arizona though the Physics Department. The course instructor was Dr. Eduardo Rozo.

---

## Overview

This Python code was written to query data from the [Illustris Database](http://www.illustris-project.org/), extract ![g_obs](https://latex.codecogs.com/gif.latex?g_{obs}), the observed gravitational acceleration, and ![g_bar](https://latex.codecogs.com/gif.latex?g_{bar}), the gravitational acceleration caused by the enclosed baryonic matter, at different radii within the first 100 objects of 10 million solar masses or more. Included ipython notebooks contain documentation for calling the query and calculation functions as well as code for finding the ![g_bar](https://latex.codecogs.com/gif.latex?g_{bar}) vs ![g_obs](https://latex.codecogs.com/gif.latex?g_{obs}) curves. It's these curves that can then be compared to a MOND (**Mo** dified **N** ewtonian **D** ynamics) fit function,

![MOND Fit](https://latex.codecogs.com/gif.latex?g_{obs}&space;=&space;\frac{g_{bar}}{1-e^{-\sqrt{g_{bar}/g^{\dagger}}}})

[Reference](/documents/1610.08981.pdf)
