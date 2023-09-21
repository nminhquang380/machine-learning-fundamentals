In this chapter you will work through an example project end to end,
pretending to be a recently hired data scientist at a real estate company. This
example is fictitious; the goal is to illustrate the main steps of a machine
learning project, not to learn anything about the real estate business. You can visit my recent [project](https://github.com/nminhquang380/austock-price-predict). Here are
the main steps we will walk through:

## 0. Working with Read Data.
    
It is best to experiment with real-world data, not artificial datasets. Fortunately, there are thousands of open datasets to choose from:
- Popular open data repositories:
    - OpenML.org
    - Kaggle.com
    - PapersWithCode.com
- UC Irvine Machine Learning Repository
  - Amazon’s AWS datasets
  - TensorFlow datasets
- Meta portals (they list open data repositories):
  - DataPortals.org
  - OpenDataMonitor.eu
- Other pages listing many popular open data repositories:
  - Wikipedia’s list of machine learning datasets
  - Quora.com
  - The datasets subreddit
## 1. Look at the big picture.
In this phase, you should answer thoroughly:
- What you want to do?
- What you have?
- How you can get what you want from what you have?
- Why you do that?
- Are there anything we should care in each step?

Some steps you can follow:
- Frame the Problem
- Select Performance Measure
- Check the Assumptions
## 2. Get the data.
For recommendation, I would say that please experiment your data in Jupyter Notebook first. It would be more easy to interact and do many experiments as you want.
- Download the Data
- Tak a quick look at data structure
- create a test set
## 3. Explore and visualize the data to gain insights.
Performing EDA is not a easy task. It depends on our data structure, and also your target. We don't have a list of questions or actions to answer sequentially. You can read online articles or search for specific notebook which performs similar task to get more information and guidance.
## 4. Prepare the data for machine learning algorithms.
Before feed data to our machine learning models, we have to prepare data for them. Like other tasks, it also depends on our data. However, there are some essential tasks we should do:
- Clean data, deal with missing, duplicated data.
- Handle Text and Categorical data.
- Feature Scaling and Transformation.
- Feature Engineering.
## 5. Select a model and train it.
After all, now is the time to use our knowledge of Machine Learning. For specific purpose and type of data, we would select different models. There are some steps:
- Select models.
- Train and Evaluate models on Training Set or using Cross-validation.
## 6. Fine-tune your model.
After you have a shortlist of models. Now you need to fine-tune them. Let's look at a few ways you can do that:
- Grid Search: you make a grid of hyperparameters and try to find the greatest combination.
- Randomized Search: use when the hyperparameters search space is large.
- Ensemble Methods: Combine different models that perform well, the ensemble often perform better than the best individual.
- Analyze the best models and their errors.
- Evaluate system on test set.
## 7. Launch, monitor, and maintain your system.