# Annals_of_Surgery_Gender

This repository contains code to reproduce the results presented in the paper 

> **Chang M, Liang JW, Stein SL, Salles A. Gender and authorship in Annals of Surgery: A nineteen-year review including the pandemic. 2024.**
  
## R package dependencies
- Data wrangling and visualization: [`tidyverse`](https://cran.r-project.org/web/packages/tidyverse/index.html), [`lubridate`](https://cran.r-project.org/web/packages/lubridate/index.html), [`reshape2`](https://cran.r-project.org/web/packages/reshape2/index.html), [`forcats`](https://cran.r-project.org/web/packages/forcats/index.html), [`ggrepel`](https://cran.r-project.org/web/packages/ggrepel/index.html), and [`gridExtra`](https://cran.r-project.org/web/packages/gridExtra/index.html)
- Robust standard errors and marginal means: [`sandwich`](https://cran.r-project.org/web/packages/sandwich/index.html), [`lmtest`](https://cran.r-project.org/web/packages/lmtest/index.html), and [`emmeans`](https://cran.r-project.org/web/packages/emmeans/index.html)

## Data
- Data on all submissions to *Annals of Surgery* from 2005 to 2023, including authors’ names, manuscript title, submission date, final decision date, and final decision (accept or reject), was provided by the journal. 