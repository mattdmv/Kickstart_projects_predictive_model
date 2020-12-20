# Kickstart projects predictive model
Kickstarter is a funding platform directed toward helping creative projects get off the ground. It's entirely driven by crowdfunding, so donations from the general public fuel these dynamic new ideas.

How does Kickstarter work?

Kickstarter is driven by creators and backers. Creators present creative project ideas, and backers fund them. Creators set up a page to display their project's details and prototypes using text, video, and photos. Project creators choose a deadline and a minimum funding goal and create reward levels for backers who pledge specific amounts. 
Once enough backers have funded the project, the creator can develop and produce their vision. If the goal is not met by the deadline, no funds are collected (all or nothing rule).

### About this project 

Purpose of this project is to try to make a model to predict if the project would be successful or failure.

Some interesting questions to answer along the analysis:
- How many backers are needed on average to have successful Kickstarter campaign?
- Are projects from certain countries more likely to be successful campaigns?
- Which categories of projects are more likely to attract more backers? 

### Dataset information 
- Source: https://www.kaggle.com/kemical/kickstarter-projects

- Content: dataset contains about 380,000 rows of data collected on crowdfunding projects hosted on Kickstarter.com. Columns are self explanatory.

- Acknowledgements: Kickstarter Platform

### Packages Used
- pandas, matplotlib, seaborn, sklearn, numpy

### Models used
- K-Nearset Neighbors, Logistic Regression, Random Forests, Artificial Neural Networks

### Results comparison 
| MODEL | ACCURACY SCORE | CROSS VALIDATION SCORE |
| ----- | -------------- | ---------------------- |
| K Nearest neighbors, k=5 | 97,10% | 97,22% | 
| Logistic regression | 95,91% | 96,10% |
| Random Forests | 98,95% | 98,98% |
| Artificial Neural Networks | 99,66% | 99,54% |

### Next steps
...
