# Ćwiczenie 1 - TIER protocol i tidy data

Original data tb.csv is available in /OriginalData folder. It's also copied to /AnalysisData.

The whole script is in /CommandFiles/Lab1.ipynb, where code is commented and its role is described.

Data after analysis is available in:
 /AnalysisData/tb.csv - copy of original tb.csv
 - iso2 - string; country of the patient. 
 - year - string; year of examination.
 - other columns - categorical variables; data on type of tuberculosis

 /AnalysisData/tb_tidy.csv - file contains cumulated information from pew.csv. Headers of file are:
 - country - string; country of the patient. 
 - year - string; year of examination.
 - cases - positive integer number; amount of cases with confirmed tuberculosis in that year
 - sex - categorical variable; patients gender
 - age - math interval; patients age
