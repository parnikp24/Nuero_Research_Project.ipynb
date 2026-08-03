# Neuro Research Project

An independent research project applying machine learning to decode 
visual categories from human fMRI brain activity, using the Haxby et al. 
(2001) dataset accessed via nilearn.

## What this does
Trains a support vector machine (SVM) classifier to distinguish between 
brain activation patterns for different visual categories (faces, houses, 
cats, chairs) using data from the ventral temporal cortex.

## Key finding
Classification accuracy was higher for visually/categorically distinct 
pairs (face vs. house: 100%, house vs. chair: 99%) than for two similar 
animate categories (face vs. cat: 82%), suggesting neural representations 
of similar categories overlap more.

## Tools used
Python, nilearn, scikit-learn, Google Colab
