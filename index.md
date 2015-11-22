---
title       : Ovulation Calculator
subtitle    : Calculates Best Days to Conceive
author      : ss
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Getting pregnant isn't always easy! Use this simple app to find out your most fertile days!


--- .class #id 

## How does the app calculate most fertile days?

In the average menstrual cycle, ovulation occurs 14 days before the menstrual period arrives -- or on day 14 of a 28-day cycle. The app uses this fact to calculate your most fertile days.


--- .class #id 

## How to use the app - 3 simple steps!!

1. Enter Date of Last Menstrual Period
2. Enter Average Length of Cycle 
3. Click the "Get Fertile Window" button

--- .class #id 

## Demo
Date of Last Menstrual Period: 11/22/2015

Average Length of Cycle: 28 days

Your best days to conceive are from:", firstday(input$lmp, input$cycle), "to", lastday(input$lmp, input$cycle))


