# Forecasting using R language practices

## Introduction

- I made this repository to solve the forecasting questions in 'Forecasting: Principles and Practice(2nd Ed.)'. The book was written by Rob J Hyndman and George Athanasopoulos. You can read online version of the book in [here](https://otexts.org/fpp2/).

### Caution

- The codes what I wrote are just my solutions, not related with official solution. They are the result of my practice, not the authors' solutions. I did my best to solve the questions as accurately as possible, but there can be wrong answers.

- Some questions ask you to download data and forecast using them. You need to download the data for the questions.

- I didn't solve the questions which aren't related with coding. I mentioned them at the bottom of each file. 

- I didn't solve the questions of Chapter 1 and 4.

## Prerequisites

- You need to understand about the concepts and algorithms behind the forecast models and evaluation methods. You can study them in [here](https://otexts.org/fpp2/).

- All codes are written in rmd(r markdown) files. Therefore you need to install R and Rstudio to open the files

- If you already installed the Rstudio, you need to check if fpp2 package is already installed. It is the most important package that I used in forecasting. If you need to install it, type below code in the console.

  install.packages("fpp2")
  
  You also need to install other packages like xlsx, rdatamarket, hts, seasonal, tseries, vars, etc.
  
## Built With

1) readme.rmd
 - Introduce about this repository.

2) Chapter2.rmd
 - 'Time series graphics'
 - learn how to make ts object and deal with it using several functions like autoplot(), frequency(), etc.
 - learn how to draw several types of plots like seasonal plot, seasonal subseries plot, scatter plots and lag plot, etc.
 - Understand what is autocorrelation and learn how to draw autocorrelation function(ACF) plot.
 - Understand what is white noise and learn how to discern white noise series using ACF plots.

3) Chapter3.rmd
 - 'The forecaster's toolbox'
 - learn how to do simple forecasting using 4 benchmark methods.
 - learn transformation methods like Box-Cox transformation and how to implement transformations to data.
 - understand the concept of fitted values and residuals, and learn about Pormanteau tests which are used to see if the residuals are like white noise series.
 - learn how to evaluate forecast accuracy.
 - learn how to get prediction intervals in different situations.
 
4) Chapter5.rmd
 - 'Linear regression models'
 
5) Chapter6.rmd
 - 'Time series decomposition'
 
6) Chapter7.rmd
 - 'Exponential smoothing'
 
7) Chapter8.rmd
 - 'ARIMA models'
 
8) Chapter9.rmd
 - 'Dynamic regression models'
 
9) Chapter10.rmd
 - 'Forecasting hierarchical or grouped time series'
 
10) Chapter11.rmd
 - 'Advanced forecasting methods'

11) Chapter12.rmd
 - 'Some practical forecasting issues'
 - Even if there aren't any exercise in the chapter, there are some examples that are worth practicing. Therefore I'm going to deal with them in here.
 
## Acknowledgments and other useful resources

- Forecasting: Principles and Practice online [textbook]( https://otexts.org/fpp2/)

- r forecast package: https://github.com/robjhyndman/forecast

- Professor Rob J Hyndman's [blog](https://robjhyndman.com/)
