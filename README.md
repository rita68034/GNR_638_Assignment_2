# GNR_638_Assignment_2
Assignment: This will have two part:

1. On the bag of words features calculated on UCM, make a three layer MLP. You can experiment on the number of nodes in the hidden layer, choice of activation etc.
2. Downscale each image of UCM to 72 x 72, linearized then, and again train a three layer MLP.
Need to Report the classification performance. Maintain the same train text split as of the bag of words case.

# Dataset
http://weegee.vision.ucmerced.edu/datasets/landuse.html

# What we did

1. We successfully extract SIFT features, cluster them using KMeans, and generate Bag of Words (BoW) histograms. Followed by training a three-layer MLP on these features and reporting classification performance with accuracy and a classification report.
2. resizing: 72x72 resolution 
3. Adding the flattening operation 
4. Training and evaluation using X_train_flat, X_test_flat maintain the same train-test split as the BoW case.

# Result

Metrics: Report accuracy, precision, recall, and F1-score for each case

# Contributor 
1. Rita Mahato 
2. Priya Nemani 
