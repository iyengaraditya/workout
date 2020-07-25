# Workout Classification
A fitness freak? Ever wondered how activity monitoring apps can classify what kind of workout you are doing tracking basic information such as the X, Y and Z coordinates, velocities and accelerations, over time. I found a really cool dataset with these quantities and some labelled workouts for training. I divided this data into two bits and erased the labels from one bit, allowing me to test the model on that bit.
Data has been collected using the FitBit API. More information about data labels can be found [http://groupware.les.inf.puc-rio.br/har](here).
The data has been cleaned and the cleaned datasets have been made available in this repository.
Four machine learning algorithms have been optimized to the data.
1. Decision Trees
2. Random Forests
3. SVMs
4. Ensemble Gradient Boost

Finally, accuracies are compared to determine which algorithm is the best fit.
