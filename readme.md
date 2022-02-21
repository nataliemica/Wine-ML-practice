# About this project
Machine learning practice using a sample dataset from `sklean`, entitled `wine`.

In this project I imported and arranged the data into a more comprehensible form using `pandas`, then tried predicting the target values of the dataset - three distinct classes that the wines belong to.

This categorical prediction was esaily done using a linear `SVC` model, and an accuracy of 92.6% was achieved. Here is a small heatmap to show the counts for what the actual vs. predicted target class was:

![heatmap_predicted_wine_class]('pred_wine_class.png')

Within this dataset there are 13 features for a wine, and the next thing I wanted to try was predicting one of these feautures based on the other 12. For this, I tried predicting the alcohol concentration of a wine with the `Ridge` regression model.

Unfortunately, the accuracy for this test is only 46%, and an example plot of the actual vs predict alcohol concentrations can be seen below:

![predicted_alc_conc]('pred_alc_conc.png')