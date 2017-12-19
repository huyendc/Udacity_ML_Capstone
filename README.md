# Capstone Project
## Predicting Loan Default in the Fannie Mae Single-Family Loan Performance Data

## Table of Contents  
- [Project Overview](#project-overview)
- [Packages](#packages)
- [Data](#data)


### <a name="project-overview"></a>Project Overview

The Federal National Mortgage Association (FNMA), commonly referenced 
as Fannie Mae, is a corporation with the purpose to expand the secondary 
mortgage market by securitizing mortgages in the form of mortgage-backed 
securities (MBS). In a nutshell, Fannie Mae acquires mortgage loans from 
primary lenders such as Wells Fargo, Chase, and Quick Loans, among others. 
After the mortgages' acquisition, Fannie Mae groups them in mortgage pool, 
which, by a diversification effect, has lower risk than the 
risk of each mortgage individually. Until the 2008 financial crisis, 
these mortgage pools (MBS) sold by Fannie Mae were considered stable 
investments; however, the crisis showed that these pools were not as 
safe as people thought. In fact, during the crisis burst, 
many people defaulted on their mortgages, causing these securities 
prices to decreases significantly, thereby severely impacting the 
performance of these investments.

Following the crisis, Fannie Mae with the intention to promote a better 
understanding of the credit performance of Fannie Mae mortgage loans, 
started providing loan performance data on a portion of its single-family 
mortgage loans. The goal of this project is to predict from Fannie Mae 
single-family performance data, those borrowers who are most at risk of 
defaulting on their loans.

### <a name="install"></a>Install

This project requires **Python 3.6+** and the following Python libraries installed:

- [NumPy 1.13.3](http://www.numpy.org/)
- [Pandas 0.20.3](http://pandas.pydata.org)
- [matplotlib 2.1.0](http://matplotlib.org/)
- [Seaborn 0.8.0](https://stanford.edu/~mwaskom/software/seaborn/)
- [scikit-learn 0.19.1](http://scikit-learn.org/stable/)
- [imbalanced-learn 0.3.1](https://pypi.python.org/pypi/imbalanced-learn)
- [missingno 0.3.7](https://pypi.python.org/pypi/missingno/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/)

Udacity recommends their students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

### <a name="data"></a>Data

The Performance and Acquisition datasets for the analysis can be downloaded from Fannie Mae [Fannie Mae website](http://www.fanniemae.com/portal/funding-the-market/data/loan-performance-data.html). A portion of its single-family mortgage loans dataset. The Single Family 
Fixed Rate Mortgage dataset contains a subset of Fannie Mae's 30-year or 
less, fully amortizing, full documentation, single-family, conventional 
fixed-rate mortgages.
