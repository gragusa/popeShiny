Next Pope?
--------------

Interactive app built in #rstats using Shiny to track the odds of the possible options for the next Pope as the cardinals arrive in Rome and go into conclave. 

Probabilites are based on odds scrapped from a large online bookmaker and updated every hour. 

##### Live Demo:

[http://glimmer.rstudio.com/dataparadigm/pope/](http://glimmer.rstudio.com/dataparadigm/pope/)

Note: username limits left the s of dataparadigms

##### How to run locally:
Download and install [R (free software environment for statistical computing and graphics)](http://www.r-project.org/)

Install the shiny library 

```r
install.packages("shiny", dependencies = TRUE)
```

Type either of the following options into your R console. 

```r
library(shiny)
runGitHub("popeShiny", "dataparadigms")
```
or

```r
library(shiny)
runUrl('https://github.com/dataparadigms/popeShiny/archive/master.tar.gz')
```

##### Alternatively:
Clone the directory

```bash
git clone https://github.com/dataparadigms/popeShiny.git 
```

Fire up the R console and type

```r
setwd('path to where you cloned the repo')
source('launch.R')
```

##### Questions?
- twitter: [datapardigms](https://twitter.com/dataparadigms)
- web: [http://www.dataparadigms.com](http://www.dataparadigms.com)


##### Disclaimers 
- The probabilities are based on odds published by an online bookmaker.  In no way, shape, or form is this an attestation nor algorithmic prediction of who the next Pope will be.   
- The house ALWAYS wins.  
- The odds are developed by the bookmaker as they see fit, this information is not released to the general public (you and I).  
- I do not claim to have any domain specific knowledge related to the Catholic Church.  
- Be skeptical of any use other than monitoring the changes in the odds over time.  

