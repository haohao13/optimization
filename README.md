# Optimization
Optimization Package: cvxpy  
Code writen on Google Colab

## Optimization Cheat Sheet
Basic optimization concepts including:
1. Optimization Overview
2. Linear Programming (LP)
3. Nonlinear Programming (NLP)
4. Quadratic Programming (QP)
5. Integer Programming (IP)
6. Dynamic Programming (DP)

## Coding Exercises

### Exercise 1: Sensitivity analysis for a content publisher website
Content publishers such as The New York Times, The Washington Post and The Wall Street Journal generate revenue by using display advertisements. The Washington Post's website contains several different sections including Sports and National. The number of views each section gets per day can be estimated by analyzing historical data. Assume that the Sports section gets six million views per day and the National section get five million views per day. Assume four companies, GEICO, Delta, T-Mobile and Capital One, wish to advertise on the Sports and National sections of the Washington Post and they contract directly with the newspaper. For each company, the contract specifies the number of times its display ads are shown in these two sections. The contracts sometimes also specify a total number of page views that can originate from any section of the newspaper. The page views promised by The Washington Post to each advertiser are summarized in the left table below. Assume that the contract also specifies that The Washington Post receives $2.40 per click-through from each of the four companies. However, not every page view leads to a click. If every 1000 views leads to 5 clicks, the click-through rate is 0.5%. Newspapers use historical data and tracking technologies to determine click-through rates. Assume that the relevant click-through rates are given in the right table below.

Contracts:
| Company | Sports | National | Total |
| -- | -- | -- | -- |
| Geico | 2 million | 1 million | - |
| Delta | - | 1 million | 2 million |
| T-mobile | 1 million | 1 million | 3 million |
| Capital One | - | - | 2 million |

Click-Through Rates:
| Company | Sports | National |
| -- | -- | -- |
| Geico | 2.5% | 0.8% |
| Delta | 2.0% | 1.0% |
| T-mobile | 1.0% | 3.0% |
| Capital One | 1.5% | 2.0% |

Click-Through Rates Ranges:
| Company | Sports | National |
| -- | -- | -- |
| Geico | From 2% to 3% | From 0.1% to 1.1% |
| Delta | From 1.5% to 2.5% | From 0.5% to 1.5% |
| T-mobile | From 0.5% to 1.5% | From 2.5% to 3.5% |
| Capital One | From 1.5% to 2.0% | From 1.5% to 2.5% |


### Exercise 2: Operations excellence for a manufacturing firm
You operate two plants, i.e., A and B. Each plant makes two products, “standard” and “deluxe”. A unit of standard gives a profit contribution of $10, while a unit of deluxe gives a profit contribution of $15.
Each plant uses two processes, grinding and polishing, for producing its products. Plant A has a grinding capacity of 80 hours per week and polishing capacity of 60 hours per week. For plant B, these capacities are 60 and 75 hours per week, respectively.
The grinding and polishing times in hours for a unit of each type of product in each factory are given in the tables below.

For Plant A:
|   | Standard | Deluxe |
| -- | -- | -- |
| Grinding | 4 | 2 |
| Polishing | 2 | 5 |

For Plant B:
|   | Standard | Deluxe |
| -- | -- | -- |
| Grinding | 5 | 3 |
| Polishing | 5 | 6 |

It is possible, for example, that plant B has older machines than plant A, resulting in higher unit processing times. In addition, each unit of each product uses 4 kg of a raw material, which we refer to as raw. The company has 120 kg of raw available per week. To start with, we will assume that plant A is allocated 75 kg of raw per week and plant B the remaining 45 kg per week. Each plant can build a very simple linear programming model to maximize its profit contribution.

### Exercise 3: Expansion strategy optimization for a hotel chain company
LQM is a middle-sized hotel chain that is considering expanding to more locations. LQM used data on 75 existing inn locations to build a linear regression model to predict “Profitability”, computed at the operating margin, or earnings before interest and taxes divided by total revenue. They tried many independent variables and came up with the final model  
Profitability=39.05-(5.41xState Population per Inn)+(5.86xPrice of the Inn)-(3.09xSquare Root of the Median Income in the area)+(1.75xCollege Student in the Area)  
All independent variables are significant and were normalized to have mean zero and standard deviation 1.

