# DSC 180A Methodology Assignment 4
## Michael Petersen m1petersen@ucsd.edu
## Section: D12 - NLP Credit Scoring 
## Mentor: Goutham Valeti

**1. What is the most interesting topic covered in your domain this quarter?**

The use of fastText to categorize transactions based on raw memos (text). Training a model to assign spending categories from raw transaction memos is fascinating because it can process millions of transactions quickly and accurately.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I would like to analyze which features in transaction history, such as spending volatility or category mix, best separate borrowers who repay from those who default.

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

I would have prioritized identifying spending patterns and creditworthiness earlier, and treated categorization as a means to that goal rather than an end in itself. I would also have used LLMs sooner to streamline categorization and fail fast, rather than spending a long time on an approach that wasn’t working.

**4. What other techniques would you be interested in using in your project?**

I would like to compare zero-shot and few-shot LLM classification against fastText on a labeled sample of transactions, measuring accuracy, runtime, and cost, to determine whether LLMs are worth their added expense for categorization.
Since our transaction dataset consists of billions of rows, I would use LLMs to create a large enough training set for fastText to then label the rest of the transactions.