# likeFADR
This provides a structural dimensional reduction method for generalized regression model, inluding FADR model and likeFADR model, which can handle ultra-high regression problems, such as applications with ultra-high dimensional and strongly correlated covariates.
## Installation
 If you are on Windows, you can 
* Install MAVE, dr,randomForest, Rcpp and RcppArmadillo by running:
```
  install.packages(c('MAVE', 'dr','randomForest', 'Rcpp','RcppArmadillo' ))
```
* Download the package as a zip file and install package from the  zip file in Rgui.exe or Rstudio.

If you are on Linux/Mac, you can 
* Install [Rtools](http://cran.r-project.org/bin/windows/Rtools/)
* Install [devtools](http://cran.r-project.org/web/packages/devtools/index.html) by running 
```
install.packages("devtools")
library(devtools)
install_github('feiyoung/likeFADR')
```
* Running the following R code to use it!
```
  library(likeFADR)
  example('FADR')
  example('likeFADR')
```
