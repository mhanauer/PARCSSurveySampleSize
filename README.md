# PARCSSurveySampleSize
---
title: "PARCSSurveySampleSize"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

393 total responses from MCCSC with six before the actual survey started.  RBBCSC stated their response rate was 
```{r}
rbbcscR = 192
rbbcscT = 225
mccscR = 393
mccscT = 862
responseRate = sum(rbbcscR, mccscR)/sum(rbbcscT, mccscT)
```
mccsc total staff = https://docs.google.com/spreadsheets/d/1n-hqENdpDWPfoUcWMJ7Kz1ksLAA1so1bE4rd8p86wa4/edit?usp=sharing

rbbcsc total staff provided from response rate on their proposal: https://docs.google.com/a/rbbcsc.k12.in.us/document/d/1FxCfPQEAeEeD_3YCSMXONAIAYQHYDRxkGnka_TPfUL8/edit?usp=sharing
