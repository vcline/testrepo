# data science profile
Vishi Cline  
October 7, 2016  

#Introduction 
This R markdown document shows the code and the plot for my datascience profile.  It also shows data from Dr. McGee's repository.

#Results 
The following displays the ranking of skill in each of the categories on a scale from 1-5, with 1 being the worst and 5 being the best.


```r
categories<-c("computer programming", "math", "statistics","machine learning", "domain expertise", "communication", "presentation skills","data visualization")
Ranking<-c(4, 3, 3, 1, 4, 4, 3, 4)
vishi<-data.frame(categories,Ranking)
vishi
```

```
##             categories Ranking
## 1 computer programming       4
## 2                 math       3
## 3           statistics       3
## 4     machine learning       1
## 5     domain expertise       4
## 6        communication       4
## 7  presentation skills       3
## 8   data visualization       4
```

```r
colours <- c("red", "orange", "blue", "yellow", "green","purple", "pink","black")
barplot(Ranking,main="Profile Distribution", xlab="categories", ylab="Ranking", col=colours)
```

![](profile_files/figure-html/unnamed-chunk-2-1.png)<!-- -->

```
## R version 3.2.1 (2015-06-18)
## Platform: x86_64-w64-mingw32/x64 (64-bit)
## Running under: Windows 8 x64 (build 9200)
## 
## locale:
## [1] LC_COLLATE=English_United States.1252 
## [2] LC_CTYPE=English_United States.1252   
## [3] LC_MONETARY=English_United States.1252
## [4] LC_NUMERIC=C                          
## [5] LC_TIME=English_United States.1252    
## 
## attached base packages:
## [1] stats     graphics  grDevices utils     datasets  methods   base     
## 
## loaded via a namespace (and not attached):
##  [1] magrittr_1.5    formatR_1.4     tools_3.2.1     htmltools_0.3.5
##  [5] yaml_2.1.13     Rcpp_0.12.6     stringi_1.1.1   rmarkdown_1.0  
##  [9] knitr_1.14      stringr_1.1.0   digest_0.6.10   evaluate_0.9
```

