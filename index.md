---
title       : Predicting the Next Word
subtitle    : Data Science Capstone
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction
This shiny app allows you to enter text into an input box.
Based on the text you enter, the app will confirm what you have entered and show a prediction of the next word.

---

## Data
This shiny app uses the English data from HC Corpora.
A random sample of the data from news, blogs and twitter was cleansed and used to build a corpus of N-grams.

---

## Prediction
Based on the input text, the app will search through the 4-gram, trigram, bigram and unigram corpus in that order until the highest occurrence of the last few words of the input text is found, and display the next word in the sequence.

---

## Have Fun!
The shiny app can be accessed via the following link:
[http://foocewei.shinyapps.io/nextword](http://foocewei.shinyapps.io/nextword)
