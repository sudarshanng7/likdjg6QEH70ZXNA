## Term Deposit Marketing
### Background:

We are interested in developing a robust machine learning system that leverages information coming from call centers. We are looking for ways to improve the success rate for calls made to customers for any product that our clients offer.
### Data Description:

The data comes from direct marketing efforts of a European banking institution. The marketing campaign involves making a phone call to a customer, often multiple times to ensure a product subscription, in this case a term deposit. Term deposits are usually short-term deposits with maturities ranging from one month to a few years. The customer must understand when buying a term deposit that they can withdraw their funds only after the term ends. All customer information that might reveal personal information is removed due to privacy concerns.

    age: age of customer (numeric)
    job - type of job (categorical)
    marital - marital status (categorical)
    education - (categorical)
    default - has credit in default? (binary)
    balance - average yearly balance, in euros (numeric)
    housing - has a housing loan? (binary)
    loan - has personal loan? (binary)
    contact - contact communication type (categorical)
    day - last contact day of the month (numeric)
    month - last contact month of year (categorical)
    duration - last contact duration, in seconds (numeric)
    campaign - number of contacts performed during this campaign and for this client (numeric, includes last contact)

Output (desired target):

y - has the client subscribed to a term deposit? (binary)
### Goal:

Predict if the customer will subscribe (yes/no) to a term deposit. Hit 81 % or above accuracy by evaluating with 5-fold cross validation and reporting the average performance score. Determine which features are relevant to finding out customers who are more likely to subscribe.

