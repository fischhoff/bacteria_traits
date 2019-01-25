bacteria\_data\_process
================
Ilya
1/25/2019

#### install and load required packages

    ## Removing package from '/Library/Frameworks/R.framework/Versions/3.4/Resources/library'
    ## (as 'lib' is unspecified)
    ## Removing package from '/Library/Frameworks/R.framework/Versions/3.4/Resources/library'
    ## (as 'lib' is unspecified)

    ## 
    ## Attaching package: 'rlang'

    ## The following object is masked from 'package:data.table':
    ## 
    ##     :=

    ## 
    ## The downloaded binary packages are in
    ##  /var/folders/0d/qm_pqljx11s_ddc42g1_yscr0000gn/T//Rtmp7Qdmuu/downloaded_packages
    ## 
    ## The downloaded binary packages are in
    ##  /var/folders/0d/qm_pqljx11s_ddc42g1_yscr0000gn/T//Rtmp7Qdmuu/downloaded_packages

    ## 
    ## Attaching package: 'dplyr'

    ## The following object is masked from 'package:glue':
    ## 
    ##     collapse

    ## The following objects are masked from 'package:data.table':
    ## 
    ##     between, first, last

    ## The following objects are masked from 'package:stats':
    ## 
    ##     filter, lag

    ## The following objects are masked from 'package:base':
    ## 
    ##     intersect, setdiff, setequal, union

    ## 
    ## Attaching package: 'reshape2'

    ## The following objects are masked from 'package:data.table':
    ## 
    ##     dcast, melt

    ## corrplot 0.84 loaded

    ## Loading required package: lattice

    ## Loading required package: survival

    ## Loading required package: Formula

    ## Loading required package: ggplot2

    ## 
    ## Attaching package: 'Hmisc'

    ## The following objects are masked from 'package:dplyr':
    ## 
    ##     src, summarize

    ## The following objects are masked from 'package:base':
    ## 
    ##     format.pval, units

    ## CHNOSZ version 1.1.3 (2017-11-13)

    ## Please run data(thermo) to create the "thermo" object

    ## 
    ## Attaching package: 'CHNOSZ'

    ## The following objects are masked from 'package:Hmisc':
    ## 
    ##     mtitle, spearman

    ## The following object is masked from 'package:dplyr':
    ## 
    ##     slice

    ## Downloading GitHub repo TIBHannover/BacDiveR@master
    ## from URL https://api.github.com/repos/TIBHannover/BacDiveR/zipball/master

    ## Installing BacDiveR

    ## '/Library/Frameworks/R.framework/Resources/bin/R' --no-site-file  \
    ##   --no-environ --no-save --no-restore --quiet CMD INSTALL  \
    ##   '/private/var/folders/0d/qm_pqljx11s_ddc42g1_yscr0000gn/T/Rtmp7Qdmuu/devtools66095ebf892a/TIBHannover-BacDiveR-7108220'  \
    ##   --library='/Library/Frameworks/R.framework/Versions/3.4/Resources/library'  \
    ##   --install-tests

    ## 

    ## Installation failed: Command failed (3)

    ## Skipping install of 'taxizedb' from a github remote, the SHA1 (7ee9741a) has not changed since last install.
    ##   Use `force = TRUE` to force installation

    ## 
    ## Attaching package: 'taxizedb'

    ## The following objects are masked from 'package:taxize':
    ## 
    ##     children, classification, downstream
