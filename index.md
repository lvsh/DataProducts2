---
title       : Pitch for Data Products Course Project App
subtitle    : 
author      : lvsh
job         : 
framework   : shower      # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## When to hit the brakes?

![Driving in traffic](assets/img/car-316709_640.jpg)

 

--- .class #id 

## When to hit the brakes?

To avoid collisions, one has to brake in time.

Stopping distance depends on driving speed. 

Can we find a way to predict stopping distance?

---

## Cars dataset to the rescue

R dataset containing speed and stopping distances for various cars (Ezekiel, 1930).


```r
data(cars)
head(cars,n=1)
```

```
##   speed dist
## 1     4    2
```

---

## Building a predictor using cars data

![plot of chunk plotdata](assets/fig/plotdata-1.png) 



---

## Check out the app

Predict stopping distance at any speed!

[https://lvsh.shinyapps.io/CourseProject](https://lvsh.shinyapps.io/CourseProject)


