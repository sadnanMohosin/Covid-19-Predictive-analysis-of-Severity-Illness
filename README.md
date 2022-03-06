# Covid 19 Predictive analysis of Severity Illness
Four kind of analysis is performed in this big dataset and they are Descriptive and Diagnostic analysis,Predictive analysis and Prescriptive analysis. Descriptive and Diagnostic analysis is done to identify hidden insights from data; Predictive analysis is done to predict severity illness determination from machine learning algorithm and prescriptive analysis is done to show how this machine learing algorithm going to help indentifying severity illness.

This dataset is imbalanced and has a lot of missing values. As we know working with missing value is challenging and thats why data cleaning and feature engineering is one of the core part of this project.

This is a classification problem and I selected **Gradient Boosting Classifiers** model for predicting severity illness.Gradient boosting classifiers are a group of machine learning algorithms that combine many weak learning models together to create a strong predictive model. Decision trees are usually used when doing gradient boosting. Gradient boosting models are becoming popular because of their effectiveness at classifying complex datasets.

To handle imbalanced data **BorderlineSMOTE** was used. I over sampled the minority class by BorderlineSMOTE and then again trained the model to see how it performs. Defference between severity illness prediction with imbalanced data and balanced data results werer compared .

For prescriptive analysis LIME(Local Interpretable Model-agnostic Explanations) was used to explain the model’s result. Prescriptive model describes how this model can be applied in the real life senario.
