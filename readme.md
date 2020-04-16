# Loan Characterics on Borrower's APR using Propser Loan Data
## by Saphal Adhikari

### Table of Contents
1. Installation
2. Project Motivation
3. Key Insights for Presentation
4. Results
5. Licensing, Authors, and Acknowledgements

<h2>Installation</h2>
You need to have anoconda or Download python and jupyter note book.

## Dataset

> The Dataset contains 113,917 loans, each row has infomation on the borrow's APR, status, borrowed amount, debt, etc. Variables with many missing values were dropped to make the Dataset more accurate.
URL :https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1547358770029000

<h2>Project Motivation</h2>


* What affects the borrower’s APR or interest rate?
* Are there differences between loans depending on how large the original loan amount was?

<h2>Key Insights for Presentation</h2>


 First, histogram plot were created to visualize the distribution on borrower's APR percentage. After exploring all possible variables related to BorrowerAPR. ProsperScore has the strongest relationship with Borrower's APR (negatively correlated). Scatter plot and Heatmap were also created to find out that ProsperScore and BorrowerAPR were negatively correlated. The third plot created multiple scatter plots (BorrowerAPR vs ProsperScore) on different letter ratings. The plots showed the lowerest rating(HR) of borrowers received the highest APR percentage, and borrowers with highest rating (AA) received the lowerst APR percentage."# Data-Exploration" 

<h2>Results</h2>

After analyzing each variables. Borrowers's APR, Borrowers's score, rating, available bank card credit and creditscore were found to be negatively correlated to Borrower's APR. Adding that that, borrower' Scores (given from 0 to 11) gave the strongest negative relationship with borrower's APR.

Borrowers with different letter ratings were also analyzed. It came out that borrowers with the lowerest rating(HR) received higher APR percentage, and borrower with high rating A(A) received lowers APR percentage. This differentiate groups of people in terms of APR received based on their rating and scores.


<h2>Licensing, Authors, and Acknowledgements</h2>

I would like to thank udacity for providing me this opportunity for this project and providing us the data frame for analysis.

### Author
Saphal Adhikari
