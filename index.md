---
title       : Basic Arithmetic Calculator
subtitle    : Assignment for Data Products Class - Coursera
author      : Viseshraj Ethirajan
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

# GOAL:
The goal is to create a Basic Arithmetic Calculator using Slidify.

1. The user should be able to provide two numbers
2. Choose the Arithmetic operation to be carried out between them like Add, Subtract, Multiply or Divide.
3. Option to choose if the output should be an absolute value.
4. Calculate button to trigger the calculation

--- .class #id 

# App Hosting
The App has been hosted in the shinyApp.io server using the deployApp() function from slidify package.

The URL to access the app is https://viseshraj.shinyapps.io/Calculator/

--- .class #id

# App Code:
The source code for the application has been posted on GITHUB.  The documentation for the steps to run the app locally is also provided in the README.md file located in the repository in GITHUB. 

Link: https://github.com/viseshraj/DataProductsAppAssignment

---

# Approach:

- Two Text boxes have been provided to input the two numbers.
- A set of radio buttons have been provided with the Add, Subtract, Multiply and Divide options.
- A check box to enable/disable the conversion of output to an absolute value.
- An action button to Calculate.
- About page for the documentation.
