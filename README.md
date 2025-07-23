# Ohwhaley Package 


This R package was made in the unit **STAT1378-Coding and Communication in Statistics** at Macquarie University (Sydney).

## How to use the package

- Install Rtools for your R version [here](https://cran.r-project.org/bin/windows/Rtools/).
- Install the package devtools :
``` r
install.packages("devtools")
``` 
- Run the command : 
``` r
devtools::install_github("juruch/ohwhaley")
```
If it doesn't work try the following :
``` r
devtools::install_github("juruch/ohwhaley", force = TRUE)
``` 
- Then you should be able to run the command :
``` r
ohwhaley::say("Hello ! ")
``` 
And there it is ! You now have a cute little talking whale.
``` r
            ------ 
           Hello !  
            ------ 
               \   
                \  
                 \
     .-'
'--./ /     _.---.
'-,  (__..-`       \
   \          .     |
    `,.__.   ,__.--/
     '._/_.'___.-`
``` 
---
You can try and run this line for some whaley puns !
``` r
ohwhaley::say()
```
