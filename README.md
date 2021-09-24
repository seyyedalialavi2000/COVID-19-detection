# paper purpose

The novel coronavirus (also known as COVID-19) was discovered in Wuhan and soon spread throughout the world, causing havoc on the economy and people's daily lives. In order to identify infected persons and care for them during the early stages of COVID-19 and decrease the virus's propagation, an accurate diagnostic technique is required. For this we represent new solution for detection of the virus.

## Dataset

click here to [download]https://github.com/seyyedalialavi2000/COVID-19-detection/tree/master/dataset/X-Ray%20Image%20DataSet) dataset

## method?

This article employs pre-trained neural networks, which is a relatively new technique. This method extracts features from X-ray images using readily available pre-trained model, DensNet169. In the second step, we use one of the feature selection methods (ANOVA) to obtain an adequate number of features for classification, and XGBoost was employed as a clasifer.

## Accuracy

For three and two class problem, we riched 92%, 98.72% Accuracy rate, respectively.

## Performance Metrics

Since our class distribution is unbalanced, we devised measurements such as precision, sensitivity, specificity, and f1-score in addition to accuracy.
