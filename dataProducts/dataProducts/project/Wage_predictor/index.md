---
title       : Naive Wage Predictor
subtitle    : Application to predict your wage based on your gender, ethnicity, education level, and marital status
author      : Lim Wei Ann
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : standalone # {standalone, draft}
knit        : slidify::knit2slides
---

## About

- The "Linear Regression" application is a naive wage predictor based on user input of their:

    1. Age via a slider   
    
    2. Education Level via radio buttons
    
    3. Ethnicity via radio buttons
    
    4. Marital Status via radio buttons


--- .class #id 


## The Fit

- The predictor is train with the "Wage" data on the "ISLR" package using a simple linear regression model.



```
##  [1] "year"       "age"        "sex"        "maritl"     "race"      
##  [6] "education"  "region"     "jobclass"   "health"     "health_ins"
## [11] "logwage"    "wage"
```

- There are many variables in the data set, but the linear regression model is fitted only with the follow variables:

    1. age

    2. education

    3. maritl

    4. race

--- .class #id 

## Using This Application

- You will be able to find out what you are expected to earn.

- Are you earning lesser than predicted? This is motivation for you to get out of your comfort zone and realise your full potential!

- How can you earn more? Will a higher education help?

- Perhaps a change in marital status may motivate you to earn more!

--- .class #id 

## Watch This Space

- Future development is in the works.

- More data is being gathered to allow you to get a more accurate prediction by considering more parameters.

- A more accurate model is being developed
