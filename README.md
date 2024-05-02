## High-level overview
The project aims to perform data preprocessing, including data handling, filtering, and transformation, as well as addressing challenges such as handling imbalanced datasets. 
It will explore various machine learning algorithms for data processing, including feature selection procedures, classification methods, clustering techniques, and association rule mining. 
Additionally, the project will focus on building models with clear interpretability, leveraging inductive rule-based approaches and ensemble classifiers. Explaining model decisions and analyzing time series data will be integral parts of the project. 
Deep learning techniques will also be explored for deep data analysis, utilizing architectures suitable for specific applications.

# Dataset Description

Dataset contain information about price movement of 200 stocks.

## Files
- `train.csv` - the training set
- `test.csv` - the test set

## Columns
- `Date` - Datetime
- `Symbol` - Stock name
- `Adj Close` - Adjusted close stock price
- `Close` - Stock price on closing time
- `High` - Highest stock price on given day
- `Low` - Lowest stock price on given day
- `Open` - Stock price on market opening
- `Volume` - Trading volume
- `Target` - Targeted value. If for a given stock there will be at least 2% increase in next 2 months.
- `Id` - Id
