# GEPD Data Scientist Project
A small task for GEPD data scientist candidates

## Overview

In this project you will recieve a biased dataset or spacer sequences and you will have to detect that bias. This task requires some biochemichal knowladge for the feature selection (i.e. feature of interest on an RNA fragment).

The data set represents a list of spacers (the CRISPR part that is being searched by the cas protein) and a Y score that reflects an cas system's fake editing effeciency (0 no editing, 1 all is edited and anything in between).

## Task

1. Select and calculate a feature set
2. Select a model and train him on the given data
3. Show a consistent prediction rate of over 90% on a test set comprising 30% of the data
4. Show importance of features in the set and make an educated guess for how the biased dataset was created.


## Questions (no need to answer in the response, for future discussion)

1. How did you select the model, what makes this model better then others?
2. what make a good biochemichal feature set? What aspect of the RNA sequence did you test?
3. What other features could be added if the repeat / tracrRNA sequence were given?


## What do I send?

A single zip file containing a:
1. requirement.txt file with the neccesery python packages
2. a jupyter notebook the contains anything from reading the CSV file, calculating the features, running the model and visualization of the results



GOOD LUCK, I hope you enjoy this small toy problem :)
