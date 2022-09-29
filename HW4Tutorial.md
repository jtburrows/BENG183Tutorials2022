# Tutorial
Special thanks to Jingtian Zhou who wrote the original version of this homework. This tutorial is written to explain methods for solving the adapted version for the 2022 course.

## Preparation
To complete this homework, using Python, R, or Matlab is viable in analysis of the provided datasets, so feel free to use any of these. However, this tutorial will focus on using python to address the questions, specifically using Jupyter Notebooks for coding. 

Below are links which can be used in order to install python and jupyter notebooks if you have not already used them:
https://wiki.python.org/moin/BeginnersGuide/Download
https://jupyter.org/install

When using jupyter notebooks, you can launch them from the command line. Lauching them from the folder in which your datasets are stored (they can also be stored in a sub-folder) is likely easiest for navigation.

## Question 3
This problem involves performing statistical tests on the datasets given, comparing the two columns of each dataset as the two groups for each statistical test.
In order to begin, accessing the information in the files can be done in several ways, but one common method is using PANDAS:

'''python
import pandas as pd
dataset1 = pd.read_csv("Q3/dataset1.txt", sep='\t', header=None)
'''
