# Hand-Written-Digit-Classification Using the KNN Algorithm.
A Machine Learning project which implements Supervised Machine Learning Technique.

## Project Brief:
The aim of this project is to classify or is to identify the handwritten digits taken from the MNIST dataset using the KNN Algorithm.

## MNIST dataset:
MNIST is a collection of handwritten digits from 0-9. Image of size 28 X 28

<img src ="https://github.com/sureshmecad/Handwritten-Digit-Classification/blob/main/AnugantiSuresh_HandWrittenDigitClassification/Hand_Written_01.JPG">

## Code Requirements:

 1.Python
 2.Numpy
 3.Pandas
 4.Matplotlib
 5.seaborn
 6.tensorflow
 7.keras
 8.opencv2 

## The KNN Algorithm:
* KNN stands for the Kth Nearest neighbour, it is one of the simplest Machine Learning Algorithm based on Supervised Learning technique.
* KNN algorithm stores all the available data and classifies a new data point based on the similarity hence its is a non-parametric algorithm.
* This means when new data appears then it can be easily classified into a well suite category by using K- NN algorithm. 
* K is the hyperparameter which defines the number of nearest neighbours taken under consideration for building the model.

## More about the MNIST data, code and working of the model:
* The MNIST database (Modified National Institute of Standards and Technology database) of handwritten digits consists of a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. Additionally, the black and white images from NIST were size-normalized and centered to fit into a 28x28 pixel bounding box and anti-aliased, which introduced grayscale levels.
* Data is imported from the MNIST dataset and since we are implementing using the Supervised Learning technique, we give our machine learning model a collection of training data (features) and what we expect the model to output for each set of that training data we pass in (labels).
* The data is divided into training and testing data, the former dataset is used for training and building the model using KNN Algorithm, the latter is used to check the working and accuracy of the built model.
* Various functions are defined for cleaning and training of the data using a few built-in functionalities. 

## Future Scope:
 The KNN algorithm used for building this model can be used for: 
* ***Building Recommendation Systems:***
   KNN is an excellent baseline approach for the systems. 
   Many companies make a personalized recommendation for its consumers, such as Netflix, Amazon, YouTube, and many more.
   
* ***Searching semantically similar documents:***
   Each document is considered as a vector. If documents are close to each other, that means the documents contain identical topics.
    
    
## Output of the model:
<img src ="https://github.com/sureshmecad/Handwritten-Digit-Classification/blob/main/AnugantiSuresh_HandWrittenDigitClassification/Hand_Written.JPG">

## Conclusion:

- This project is basic implementation of Supervised machine learning using the KNN Algorithm, the model is built for classifying the handwritten digits from the MNIST dataset.
- The KNN algorithm can further be extended to build models based on supervised machine learning 
