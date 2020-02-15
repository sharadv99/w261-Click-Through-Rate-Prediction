# Click-Through-Rate Prediction

--Data Science project at UC Berkeley--  
--Team: [Sharad Varadarajan](https://www.linkedin.com/in/sharadv/), [Cameron Kennedy](https://www.linkedin.com/in/cameron-kennedy-profile/), [Julia Buffinton](https://www.linkedin.com/in/juliabuffinton/), [Ram Iyer](https://www.linkedin.com/in/ram-iyer-ca/)-- 

Description
-------------

Given a large dataset containing clicks on advertisements served by Criteo from Kaggle, we sought to use our knowledge of large scale ML to build a scalable machine learning model to predict whether a user would click on a certain advertisement. The data contained 46 million records with an extremely sparse 33 million features. We developed a "homegrown" implementation  of logistic regression in Python using Spark (without MLlib) and evaluated its performance using log loss and accuracy. Our best model achieved a log loss of 0.650 and accuracy of 0.645.

The files in this directory contain the presentation notebook and code for this project.

Please see the full codebook [here](https://github.com/sharadv99/w261-Click-Through-Rate-Prediction/blob/master/LargeScaleML.ipynb).

Tech Stack/Methods
---------

- Pyspark
- Big Data analysis
- Feature Engineering/EDA for sparse dataset
- Google Cloud
- Logistic Regression (w/ Log Loss)
- Gradient Descent
- Ridge and Lasso Regularization
