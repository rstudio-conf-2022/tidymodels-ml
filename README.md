Machine Learning with tidymodels
================

### rstudio::conf 2022

by Julia Silge + Max Kuhn + David Robinson

-----

:spiral_calendar: July 25 and 26, 2022  
:alarm_clock:     09:00 - 17:00  
:hotel:           \[ADD ROOM\]  
:writing_hand:    [workshops.tidymodels.org](https://workshops.tidymodels.org/)

-----

## Overview

This workshop provides an introduction to machine learning with R using the [tidymodels](https://www.tidymodels.org/) framework, a collection of packages for modeling and machine learning using [tidyverse](https://www.tidyverse.org/) principles. We will build, evaluate, compare, and tune predictive models. Along the way, we'll learn about key concepts in machine learning including overfitting, resampling, and feature engineering. Learners will gain knowledge about good predictive modeling practices, as well as hands-on experience using tidymodels packages like parsnip, rsample, recipes, yardstick, tune, and workflows.

Find slides and class materials at <https://workshops.tidymodels.org/>.


## Is this workshop for me? 

This course assumes intermediate R knowledge. This workshop is for you if:

-   You can use the magrittr pipe `%>%` and/or native pipe `|>`
-   You are familiar with functions from dplyr, tidyr, and ggplot2
-   You can read data into R, transform and reshape data, and make a wide variety of graphs

We expect participants to have some exposure to basic statistical concepts, but NOT intermediate or expert familiarity with modeling or machine learning.

## Preparation

Please join the workshop with a computer that has the following installed (all available for free):

-   A recent version of R, available at <https://cran.r-project.org/>
-   A recent version of RStudio Desktop (RStudio Desktop Open Source License, at least v2022.02), available at <https://www.rstudio.com/download>
-   The following R packages, which you can install from the R console:

```{r}
#| eval: false
#| echo: true
install.packages(c("doParallel", "embed", "forcats",
                   "lme4", "ranger", "remotes", "rpart", 
                   "rpart.plot", "stacks", "tidymodels",
                   "vetiver", "xgboost"))
remotes::install_github("topepo/ongoal@v0.0.2")
```

## Schedule

### Day 1

| Time          | Activity         |
| :------------ | :--------------- |
| 09:00 - 10:30 | Session 1        |
| 10:30 - 11:00 | *Coffee break*   |
| 11:00 - 12:30 | Session 2        |
| 12:30 - 13:30 | *Lunch break*    |
| 13:30 - 15:00 | Session 3        |
| 15:00 - 15:30 | *Coffee break*   |
| 15:30 - 17:00 | Session 4        |

### Day 2

| Time          | Activity         |
| :------------ | :--------------- |
| 09:00 - 10:30 | Session 1        |
| 10:30 - 11:00 | *Coffee break*   |
| 11:00 - 12:30 | Session 2        |
| 12:30 - 13:30 | *Lunch break*    |
| 13:30 - 15:00 | Session 3        |
| 15:00 - 15:30 | *Coffee break*   |
| 15:30 - 17:00 | Session 4        |

## Instructor

Julia Silge is a data scientist and software engineer at RStudio PBC where she works on open source modeling tools. She is an author, an international keynote speaker, and a real-world practitioner focusing on data analysis and machine learning. Julia loves text analysis, making beautiful charts, and communicating about technical topics with diverse audiences.

Max Kuhn is a software engineer at RStudio. He is currently working on improving R’s modeling capabilities. He was a Director of Nonclinical Statistics at Pfizer Global R&D in Connecticut. He was applying models in the pharmaceutical and diagnostic industries for over 18 years. Max has a Ph.D. in Biostatistics. Max is the author of a number of R packages for techniques in machine learning and reproducible research and is an Associate Editor for the Journal of Statistical Software. He, and Kjell Johnson, wrote the book _Applied Predictive Modeling_, which won the Ziegel award from the American Statistical Association, which recognizes the best book reviewed in Technometrics in 2015. Their new book, _Feature Engineering and Selection_, was released in 2019.

David Robinson is a data scientist at Heap. His interests include statistics, data analysis, education, and programming in R. David is the co-author with Julia Silge of the tidytext package and the O'Reilly book _Text Mining with R_. David is also the author of the broom and fuzzyjoin packages, and of the e-book _Introduction to Empirical Bayes_. David previously worked as Chief Data Scientist at DataCamp and as a data scientist at Stack Overflow, and received a PhD in Quantitative and Computational Biology from Princeton University.


-----

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is
licensed under a [Creative Commons Attribution 4.0 International
License](https://creativecommons.org/licenses/by/4.0/).
