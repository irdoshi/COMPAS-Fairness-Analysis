# COMPAS-fairness

In the project, here's a breakdown of what I focused on:

- Examined the COMPAS algorithm, a case management and decision support tool used in the US criminal justice system, and reviewed an investigative report that suggested racial bias in its outcomes.
- Worked with a subset of the dataset compiled from public records in Florida, filtering it to include only Caucasians and African-Americans.
- Created a new variable based on the COMPAS risk score to classify individuals as low risk or high risk.
- Analyzed the recidivism rates for both low-risk and high-risk individuals, as well as for African-Americans and Caucasians.
- Created a confusion matrix comparing COMPAS predictions for recidivism with the actual two-year recidivism rates and interpreted the results.
- Assessed the accuracy of the COMPAS classification and examined how its errors were distributed. I also questioned whether I would feel comfortable with judges relying on COMPAS for sentencing guidelines.
- Repeated the confusion matrix calculation and analysis for African-Americans and Caucasians separately, evaluating the accuracy and false positive/negative rates.
- Considering the overall recidivism rates for Black and White individuals, I provided my opinion on whether the COMPAS algorithm can be considered "fair" and justified my answer.
- Attempted to create a model that didn't include gender and race initially, aiming to predict recidivism based on other available variables.
- Discussed and selected an appropriate model performance measure for the task, considering metrics such as accuracy, precision, and recall.
- Split the data into training and validation sets, developed a model on the training set, and fine-tuned it to achieve the best performance on the validation set. I reported the performance of the model.
- Examined whether including gender as a variable improved the model's performance significantly.
- Explored the impact of adding race as a variable and evaluated whether it enhanced the model's performance.
- Discussed the results obtained from my model, comparing them to the original COMPAS model. I also considered the role of gender and race in improving predictions and addressed the question of whether judges should utilize such models.
