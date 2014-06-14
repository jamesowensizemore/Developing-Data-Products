---
title       : A Simple Body Mass Index Calculator
subtitle    : 
author      : J. Owen Sizemore
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
-------------------

## Purpose of App

#### With the growing obesity epidemic in the United States it is important to have an easy way for users to determine if they have an unhealthy weight.

-----------------

## User steps

#### To use the calculator the user must enter the following information

1. Height in feet and inches
2. Weight in pounds

#### The calculator will then take the input information and output the user's BMI

-----------------------------------

## Method of Calculation 

#### The calculator works as follows:

1. Converts the input height into inches
2. Calculates the BMI as
 $$ BMI = \frac{703*(Weight)}{(Height)^2}  $$

-----------------------------------

## Example Calculation

#### To give a simple example. If a user inputs a height of 5 feet 6 inches and a weight of 130 pounds then the calculator will output a BMI of


```r
(703 * 130)/(12 * 5 + 6)^2
```

```
## [1] 20.98
```

