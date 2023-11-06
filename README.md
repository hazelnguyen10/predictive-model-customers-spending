# Predictive model of the expenditure on products in the Wine category

As a key player in the Brazilian food delivery sector, in 2021, iFood enjoyed 86% of market share nationally, with order volume 16 times higher than its nearest competitor, UberEats ([Reinaldo, 2020](https://d3.harvard.edu/platform-digit/submission/ifood-delivers-great-results-in-brazil-going-beyond-connecting-restaurants-with-customers/#:~:text=iFood%20delivers%20great%20results%20in%20Brazil%20going%20beyond%20connecting%20restaurants%20with%20customers.,-By%20Reinaldo%20Fioravanti&text=From%20delivering%20food%20to%20improving,iFood%20seems%20to%20be%20promising.)). As UberEats withdrew from Brazil in 2022 and Didi Food does not operate in the country, this giant is close to being a virtual monopoly ([Marília, 2023](https://restofworld.org/2023/ifood-brazil-delivery-app/)).

With a focus on coupons ([Marília, 2023](https://restofworld.org/2023/ifood-brazil-delivery-app/)), it is critical for iFood to address and spend marketing budget on the correct target customers which yield the most returns for the company (profit, market share, etc.). However, considering the hugely diverse product categories of iFood, it might be overly overwhelming and time-consuming to take into account all available product categories and their influencing factor at once. Hence, this project only focuses on a smaller with the primary goal is to generate a model being able to accurately predict the money spent on Wine products in the last two years (variable `MntWines`) for a given customer.

## Data set
The **Marketing Dataset** (`ifood_marketing.csv`) is a ‘fictional’ dataset on the effects of marketing campaigns which consists of multiple variables of the customers. It measures socioeconomic variables of the customers such as age, level of education, income, number of children in the household, etc. The expenditure of the customers in several food categories (fish, meat, wine, etc.) is also measured. Finally, participation of the customers in a series of marketing campaigns was also measured.

* Data from the original campaign can be found [here](https://github.com/nailson/ifood-data-business-analyst-test/tree/master)
  
* Description of the meaning of the variables in the dataset can be inferred from the variable name, and details for most of them can be found [here](https://raw.githubusercontent.com/nailson/ifood-data-business-analyst-test/master/dictionary.png).

*Note: The dataset was used as part of a recruitment process for data analysts. The dataset as well as some tasks were released, and interested data analysts would send their reports back to the company. The original tasks are different from the ones in this project.*

## Tasks
1. Handled data integrity problems (missing/duplicated data, inconsistent format, datetime data, etc.)
2. Conducted exploratory data analysis
3. Conducted variables selection and hyperparameter search to fine-tune candidate models from three model families: linear, kNN, and LASSO regression
4. Conducted model selection to choose the best predictive model of the expenditure on products in the Wine category
5. Proposed strategy to handle asymmetric errors in the prediction
6. Discussed about potential fairness problems and suggested approaches to mitigate them



