explore-packages.R
================
august.jernbom
2019-06-11

``` r
.libPaths()
```

    ## [1] "C:/Users/august.jernbom/Documents/R/win-library/3.6"
    ## [2] "C:/Program Files/R/R-3.6.0/library"

``` r
ipt <- head(installed.packages(),5)
ipt
```

    ##            Package     
    ## abind      "abind"     
    ## assertthat "assertthat"
    ## backports  "backports" 
    ## BAf        "BAf"       
    ## base64enc  "base64enc" 
    ##            LibPath                                               Version
    ## abind      "C:/Users/august.jernbom/Documents/R/win-library/3.6" "1.4-5"
    ## assertthat "C:/Users/august.jernbom/Documents/R/win-library/3.6" "0.2.1"
    ## backports  "C:/Users/august.jernbom/Documents/R/win-library/3.6" "1.1.4"
    ## BAf        "C:/Users/august.jernbom/Documents/R/win-library/3.6" "1.6"  
    ## base64enc  "C:/Users/august.jernbom/Documents/R/win-library/3.6" "0.1-3"
    ##            Priority Depends       
    ## abind      NA       "R (>= 1.5.0)"
    ## assertthat NA       NA            
    ## backports  NA       "R (>= 3.0.0)"
    ## BAf        NA       "R (>= 2.10)" 
    ## base64enc  NA       "R (>= 2.9.0)"
    ##            Imports                                                                                      
    ## abind      "methods, utils"                                                                             
    ## assertthat "tools"                                                                                      
    ## backports  "utils"                                                                                      
    ## BAf        "dplyr, purrr, MDimNormn, Useful4me, whisker, methods, rrcov,\nknitr, rmarkdown, Rtsne, drc,"
    ## base64enc  NA                                                                                           
    ##            LinkingTo Suggests             Enhances License        
    ## abind      NA        NA                   NA       "LGPL (>= 2)"  
    ## assertthat NA        "testthat, covr"     NA       "GPL-3"        
    ## backports  NA        NA                   NA       "GPL-2"        
    ## BAf        NA        "parallel, testthat" NA       "GPL-3"        
    ## base64enc  NA        NA                   "png"    "GPL-2 | GPL-3"
    ##            License_is_FOSS License_restricts_use OS_type MD5sum
    ## abind      NA              NA                    NA      NA    
    ## assertthat NA              NA                    NA      NA    
    ## backports  NA              NA                    NA      NA    
    ## BAf        NA              NA                    NA      NA    
    ## base64enc  NA              NA                    NA      NA    
    ##            NeedsCompilation Built  
    ## abind      "no"             "3.6.0"
    ## assertthat "no"             "3.6.0"
    ## backports  "yes"            "3.6.0"
    ## BAf        "no"             "3.6.0"
    ## base64enc  "yes"            "3.6.0"
