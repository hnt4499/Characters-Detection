# Characters Detection
The following advanced Deep Learning techniques was used to achieve a private leaderboard rank of 12/56 (top 20%):
- Because the training and test set was resized to feed to the model, a large proportion was corrupted. Hence, the dataset is so hard to train on. EDA was used to perform analysis on the training set, check for data missing, anomalies and correlation.
- Use Grid Search and Data Visualization to find out the best structure and fine-tune all the hyperparameters.
- VGG19 was found to be the suitable model for this problem, and used to train on the Goolge Street View dataset.
