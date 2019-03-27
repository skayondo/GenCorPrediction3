
<!-- README.md is generated from README.Rmd. Please edit that file -->

# GenCorPrediction

## Description

This repository contains information and code for replicating the
analyses performed in the article below:

Article Title: *Multi-Trait Improvement by Predicting Genetic
Correlations in Breeding Crosses*  
Journal: *Genetics* (under review)  
Authors: Jeffrey L. Neyhart, Aaron J. Lorenz, and Kevin P. Smith  
Article URL: TBD  
Preprint URL:

## Navigation

### Data

Data used in this study are available from the [Triticeae
Toolbox](https://triticeaetoolbox.org/barley). See [this
README](https://github.com/neyhartj/PopVarVal/tree/master/Data)
(external repository) for instructions on accessing this data.

### Code

The Scripts subfolder contains the code used to run the simulations and
the analyses outlined in the article above. See [this
README](https://github.com/neyhartj/GenCorPrediction/tree/master/Scripts)
for information on the scripts and their intended execution order.

Three scripts in this directory are used by all other scripts:

1.  `source.R` - loads packages, creates directory links, and loads
    data.
2.  `source_MSI.R` - runs script \#1 with modifications for the
    Minnesota Supercomputing Institute.
3.  `source_functions.R` - loads additional functions into the
    environment.
