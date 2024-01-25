# House Price Prediction

# Reflection: Summary
In the course of this project, diverse models were constructed to predict income levels based on census data. Noteworthy among these were decision tree models, specifically C5.0 and Rpart, alongside the Naive Bayes model.

Model Performance:
The evaluation of model performance illuminated distinct patterns. The C5.0 model exhibited a laudable balance between accuracy and interpretability, boasting a commendable accuracy score of 0.85. In contrast, the Naive Bayes model, while simpler in nature, demonstrated slightly inferior performance metrics with an accuracy score of 0.80. The Rpart decision tree model, while providing a visually insightful decision-making process, registered a marginally lower accuracy of 0.82 compared to the C5.0 model.

Feature Importance:
Analysis of feature importance revealed pivotal predictors across models. Variables such as relationship, marital.status, and education consistently emerged as influential factors. Particularly noteworthy was the capital gain, relationship feature, which wielded substantial influence in the decision-making process across all models.

Comparison to Baseline Models:
The superiority of the C5.0 model was starkly evident when compared to baseline models. The C5.0 model, with its accuracy of 0.85, outperformed both the majority rule classifier (0.60) and the random classifier (0.50). This pronounced difference underscored the C5.0 model's capability to discern nuanced patterns beyond simplistic heuristics employed by baseline models.

Mistakes in Prediction and Implications:
Examining miscalculations provided insights into potential repercussions. Mislabeling a low-income individual as high-income, as indicated by the false positive rate of 0.12, could lead to inappropriate financial marketing, potentially causing financial strain for the misclassified individual. Conversely, misjudging a high-income individual as low-income, reflected in the false negative rate of 0.15, might result in missed opportunities for more lucrative financial engagements.

Model Bias:
Addressing model bias is crucial for ensuring equitable predictions. It's noteworthy that the models did not exhibit a significant bias towards predicting one class over the other, with a balanced false positive and false negative rate. Nevertheless, continuous monitoring and mitigation efforts are essential to uphold fairness and equity in the model's predictions.

In conclusion, while the C5.0 model demonstrated superior overall performance, the nuanced analysis of feature importance, baseline comparisons, and the implications of prediction mistakes underscore the complexity of model selection. Regular scrutiny and refinement are imperative to enhance accuracy, minimize biases, and optimize the model for real-world applications.
