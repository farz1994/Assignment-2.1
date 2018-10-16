1. How to Import SAS XPORT files into R with the foreign package?
Using read.xport() function of foreign library we can import SAS XPORT files.

library(foreign)

data <- read.xport()

2. How to Import SAS Files into R with the Haven package?
Using read_sas() function of Haven library we can import SAS XPORT files.
library(haven)

data <- read_sas()

3. How to read Weka Attribute-Relation File Format (ARFF) files in R?

Data from Weka Attribute-Relation File Format (ARFF) files can be read in with the read.arff() function:

library(foreign)

data <- read.arff("")


4. How to read a heavy csv/tsv file using readr package?

library(readr)

mydata <- read_tsv()

mydata <- read_csv()
