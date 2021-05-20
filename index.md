---
layout: default
---

## Summary

This package performs diagnostic tests of multiplicative interaction models and plots flexible marginal effects of a treatment on an outcome across different values of a moderator, supporting linear models and GLM models.

**Authors**: Jens Hainmueller, Jonathan Mummolo, Yiqing Xu and Ziyi Liu (maintainer)

Please email all comments/questions to zyliu2020@uchicago.edu.

**Reference**: How Much Should We Trust Estimates from Multiplicative Interaction Models? Simple Tools to Improve Empirical Practice. Political Analysis, Vol. 27, Iss. 2, April 2019, pp. 163–192.

**Date**: May 12, 2021

**Version**: 1.2.6 (major syntax change) [**CRAN**](https://cran.r-project.org/web/packages/interflex/index.html) [**Github**](https://github.com/xuyiqing/interflex)

**Users Guide Markdown**
- [Linear Models](http://yiqingxu.org/software/interaction/RGuide.html)
- [GLM Models](http://yiqingxu.org/software/interaction/RGuide_glm.html)

# Table of contents

- [**Installation**](#Installation)
- [**Simulated Datasets**](#Simulated-Datasets)
- [**Raw Plot**](#Raw-Plot)
- [**GAM Plot**](#GAM-Plot)
- [**Linear Estimator**](#Linear-Estimator)
  - [**Uncertainty Estimates**](#Uncertainty-Estimates)
- [**Binning Estimator**](#Binning-Estimator)
- [**Kernel Estimator**](#Kernel-Estimator)
- [**Support for GLM Models**](#Support-for-GLM-Models)
- [**Fully Moderated Model**](#Fully-Moderated-Model)
- [**Flexible Visualization Options**](#Flexible-Visualization-Options)
- [**Estimate the Difference in Treatment Effects**](#Estimate-the-Difference-in-Treatment-Effects)
- [**Past version update notes**](#Past-version-update-notes)

# Installation

You can install the interflex package from **CRAN**:
```r
install.packages('interflex', type = "source", repos = 'http://cran.us.r-project.org') 
```
or you can install the up-to-date development version from **Github**:
```r
install.packages('devtools', repos = 'http://cran.us.r-project.org') # if not already installed
devtools::install_github('xuyiqing/interflex')
```

**Note:**

1. Mac users who have updated to MacOS Big Sur will likely encounter compilation problems. See [here](http://yiqingxu.org/public/BigSurError.pdf) for a potential solution.

2. (old) Mac users who encounter clang: error: unsupported option ‘-fopenmp’, please consider (1) updating your R and/or (2) installing new R macro tools from Github.

3. (old) Mac users who encounter “-lgfortran” or “-lquadmath” error during installation, please check out the solution here. Typing the following two lines of code in your Terminal should solve this problem.

# Simulated Datasets

Now let’s load the package as well as four simulated toy datasets:
```r
library(interflex)
data(interflex)
```

# Raw Plot

# GAM Plot

# Linear Estimator

## Uncertainty Estimates

# Binning Estimator

# Kernel Estimator

# Support for GLM Models

# Fully Moderated Model

# Flexible Visualization Options

# Estimate the Difference in Treatment Effects

# Past version update notes


Markdown is a lightweight and easy-to-use syntax for styling your writing.


```markdown
Syntax highlighted code block


# Header 1
# Header 2 

# Header 3

- Bulleted
- List
- 

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/lzy318/interflex_page/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.


