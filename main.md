# Understanding Data Analytics

general remarks:

- remember learners of aims, keep big picture in sight
	- understand the data science landscape (to see what infrastructure / staff is needed)
	- apply data analytics to see how it works, what can be done, how it could be useful

- show were we at, summarize
- hard to justify big stacks with mickey mouse examples
- the course is acompanied with R


## about me

- why i teach this course:
	- promote open source
	- see what's needed in practice 

- all course members should introduce themselves

## Background Check 

interactive bullet chart:

- statistics
- programming
- database


## Inspiration

- what data analytics can do
	- 1 million lines of code
	- seasonal.website app (maybe also seasonal viewer, cause of internet con)
	- mobile phone 
	- choropleth maps


## Tools

- R
- Python 
- R Studio
- R Studio Server
- PostgreSQL 
- Microsoft SQL Server
- Azure
- AWS
- github
- gitlab
- Oracle
- Julia
- pandas
- numpy
- mongoDB
- Cassandra
- hadoop
- elastic



## Minimal Example Stack

- Programming Language: R Language for Statistical Computing
- IDE: R Studio (Server)

- Version Control: Git
- Database: PostgreSQL


## The R language for Statistical Computing

- Interpreted / Scripting language
- Open Source, license cost free
- well established in academia and business (Microsoft backed)
- large, vivrant community
	- more than 10'000 extension packages on CRAN
	- more than 200'000 questions on stackoverflow.com
	- various mailing lists
	- elaborate documentation
	- R Core Team


## About IDE's, editors 

- R console
- R Gui (Mac)
- Eclipse Plugin
- REPL solutions 
- R Studio


## Introduction to R Studio

- 4 Panes, follow me to get LTR workflow
- script window
- console 
- short cut cmd+enter: run selection
- short cut ctrl+1, ctrl+2: switch windows
- short cut ctrl+L: clear console screen
- short cut command+D: multiple cursors @instances
- file explorer
- plot window
- .Rproj

## Basic R Objects

- vector
- matrix
- data.frame
- list

## Brackets and braces 

- **[row,col]**: Index
- **{}**: function or loop body
- **()**: function parameters

## Basic functions

- ls()
- rm()
- c()
- matrix()
- data.frame()
- list()
- head()
- tail()
- str()
- function()
- lapply()
- data()


## Getting help

- ?function name
- Stack overflow Questions tagged R


## Task I Working on a dataset (mtcars)

1. get an idea about size and structure
	- class
	- structure
	- head / tail

2. get an idea about distribution of variables
	- summarize
	- visualize
	- test

3. inferential statistics / modelling
	- variance is information
	- model choice


# Introduction


## Summary I

- a scripting language is a good start
- understanding a language helps to remember syntax
- many tasks can be solved w/o database, larger stack


# How About Real Data ?


## Types of datasets: time series

ts1 <- ts(rnorm(300), start = c(1995,1), frequency = 12)
ts2 <- ts(rnorm(100), start = c(1995,1), frequency = 4)

examples: monthly revenues over time, stocks, log files


## Types of datasets: cross sectional data

data(mtcars)



## Types of datasets: panel data (longitudinal and cross sectional)


examples: German socio-economic panel, studies with follow-ups



## How to represent different types of datasets? 

**Data structures**

- vectors: one dimensional
- key-value-pairs
- rectangular
- nested


## Task II

- try functions like length(), nrow() on different objects
- explore data types, try functions like sum(), nchar() on different vectors
- put several objects in a list


## Summary II


- different data types ask for different methods
- different datasets need different representation

**Questions**:

- What type of data do our research questions need? 
- What type of data do our processes generate?


## Data Generating Processes

- logging
- tracking
- surveys / observation
- scraping / mining 


## Collecting Data (from different sources)

- simulate
- record: devices (IoT)
- track: websites, social media, Google Analytics
- campaign: Google Adwords
- read in
	- statistical offices, studies
	- data vendors (bloomberg, datastream, macrobond, quandl)



## Manage and Archive Data: file formats

- standard text based formats
	- .csv
	- .xml 
	- .xlsx
	- .json 

- binaries 
	- .RData
	- .xls
	- .dta
	- .dat
	- .feather
	- ...

## Manage and Archive Data: databases

- relational
	- PostgreSQL
	- Oracle
	- Microsoft SQL Server
	- MySQL

- non-relational
	- Elastic
	- mongoDB
	- cassandra


## Summary III



# Output

## Visualize 

- interactive
	- data driven documents (d3)
	- shiny
	- dash
	- highcharts
	- dygraphs
	- ...

- print

=> web browser 


## Report

- knitr (LaTeX + R code snippets)
- rmarkdown (markdown + R code snippets)
- reporteR (edit powerpoint from an R script)


## Summary IV


# Beyond Descriptive Statistics


# Advanced Statistical Methods


- cluster analysis
- factor analysis
- principal component
- regression
	- linear
	- probit / logit
	- multinomial 
- machine learning
	- supervised 
	- unsupervised
- seasonal adjustment


## Overall Summary


# Links
http://101.datascience.community/2015/10/24/analytics-vs-data-science/

packs:
libcurl4-openssl-dev
latex package framed
openssl-devel






