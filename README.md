# Signature-Verification
run working.m 
From the above extracted features, a feature vector is formed and then normalized to train the neural network. In the confirmation stage, the sign to be tried is pre-handled and include extraction is performed on pre prepared test signature picture. In the wake of normalizing an element vector it is taken care of to the prepared neural system which will arrange a signature as an authentic or fake.

Some other verification includes using SVM (support Vector Machine), Error Propagation ANN, Root Mean Squared Error (RMSE) etc. All these have different accuracy and more detailed information in included in the comparison table
In Matlab I used the following two functions to match the features detected using Harrison feature function to get the output shown in figure 3.


➢	indexPairs = matchFeatures(features1,features2) returns lists of the coordinating highlights present in  include sets. The images entered are binary Features objects 

➢	showMatchedFeatures(I1,I2,matchedPoints1,matchedPoints2)- pictures the relating points. You can see the impact of interpretation between the two pictures in      spite of a few wrong matches.
