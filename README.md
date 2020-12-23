# Machine Learning - Regression: House Pricing Models Comparison

### Main Objective:** Perform the steps requested and find the best regression model.

  This is a full Data Science project with the objective to train
  and compare Machine Learning Regression Models for a House Sales in 
  King County, USA.

  After loading the dataset, there was a stage of Data Wrangling
  in order to prepare the data to a viable format.
  Then, I performed a Exploratory Data Analysis, where I got 
   some informative visualization from the data, backed up by
  numerical measures, for correlation. 

  Stage 4 was Model Development, where I created different
  regression models with different methods for comparison, using
   first one feature that had a weak correlation with the target
  then escalated until using the top 11 features most correlated to it.
  Also a pipeline was created to apply polynomial features transformation.
  Ridge regression and Polynomial Features transformation showed a significative
  improvement on models.

  Final Stage was Model Evaluation and Refinement, where I split the
  data into training and testing sets and trained a Ridge Regression model
  using the top 11 features most correlated to the targets, where I got a 
  R-squared of 64.8% with the test set data. Then, I trained a Ridge Model with
  the polynomial transformation of those same features, and I got a better model,
  with R-squared of 70%.

**- Results:** The Combination of Ridge Regression and Polynomial transformation applied to
the top11 most correlated features resulted in the best model, with a score of 70%.

**- Packages:** Matplotlib, Seaborn, Pandas, Numpy, Scikit-learn

**- Keywords:** Pipeline, Linear Regression, Multiple Linear Regression, Polynomial Regression, Ridge Regression,
Model Evaluation, Statistical Correlation
