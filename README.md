# Credit Risk Prediction

This project aims to predict financial distress (e.g., delinquency of 90+ days or worse) within the next two years using various credit-related features. The dataset used for this project is from the [Give Me Some Credit](https://www.kaggle.com/competitions/GiveMeSomeCredit/data) competition on Kaggle.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to build a machine learning model that can accurately predict whether an individual will experience financial distress within the next two years. This can help financial institutions make better lending decisions and manage credit risk more effectively.

## Dataset

The dataset contains the following features:

1. **SeriousDlqin2yrs**: Binary target variable indicating financial distress.
2. **RevolvingUtilizationOfUnsecuredLines**: Total balance on credit cards and personal lines of credit.
3. **Age**: Age of borrower in years.
4. **NumberOfTime30-59DaysPastDueNotWorse**: Number of times borrower has been 30-59 days past due.
5. **DebtRatio**: Monthly debt payments divided by monthly gross income.
6. **MonthlyIncome**: Monthly income of the borrower.
7. **NumberOfOpenCreditLinesAndLoans**: Number of open loans and lines of credit.
8. **NumberOfTimes90DaysLate**: Number of times borrower has been 90 days or more past due.
9. **NumberRealEstateLoansOrLines**: Number of mortgage and real estate loans.
10. **NumberOfTime60-89DaysPastDueNotWorse**: Number of times borrower has been 60-89 days past due.
11. **NumberOfDependents**: Number of dependents in the family.

## Installation

To run this project, you need to have Python and the following libraries installed:

- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib
- tensorflow (if using neural networks)

You can install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn seaborn matplotlib tensorflow
