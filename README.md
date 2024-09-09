# Helmet Use for Cyclists Consuming Alcohol

# Author: Daniel Brock

# Date: 09/09/2023

This project aims to determine the association between alcohol consumption and helmet use in pedalcyclists 🚲

Data source: The National Trauma Data Bank's Trauma Quality Programs Participant Use File (NTDB TQP) from the American College of Surgeons.

**Instructions for Running Code:** 
1. Place NTDB TQP annual files (2017-2021) in a file directory
2. 01_TQP_Parser.ipynb extracts files for pedalcylist injuries
3. 02_TQP_Merger.ipynb concatenates all years into centralized files and removes yearly variation in formatting
4. 03_Statisical_Analysis.Rmd generates statisical tables and figure graphs
5. 04_Feature_Selection.ipynb selects features for logistic regression analysis.

We envision this research providing a basis for preventing alcohol-associated biking injuries and improving safety practices.

We found a significant negative association between helmet use and blood alcohol concentration in trauma patients. The major findings can be summarized in figure 1 of the manuscript: 
![](figures/Figure%201_GitHub.jpg)