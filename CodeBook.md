---
title: "Cleaning_Data_Assignment"
output: html_document
date: "2022-11-05"
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## Code Book

The text file "tidy_data.txt" consists of the average of each variable from the Human Activity Recognition Using Smartphones Data Set


## Description

Data in dataset contains 180 rows and 68 columns for mean and
standard deviation

The base data is grouped by the following values to build mean value and the standard deviation std()
1. subject - The ID of the test subject
2. activity - The type of activity performed when the corresponding measurements were taken.

Activity column has 6 types as listed below.

1.WALKING

2.WALKING_UPSTAIRS

3.WALKING_DOWNSTAIRS

4.SITTING

5.STANDING

6.LAYING
