<a name="br1"></a> 

**Facial Emotion**

**Recognition**

Liangyu Wang



<a name="br2"></a> 

INTRODUCTION

**Facial emotion recognition holds**

**significant importance in various**

**business contexts due to its potential**

**impact on customer experience,**

**employee well-being, and overall**

**business performance.**

• **Gauge customer reactions to products,**

**services, or advertisements.**

• **Facial emotion recognition can help**

**businesses assess customer**

**satisfaction levels in real time.**

• **Businesses that prioritize employee**

**well-being often leverage facial**

**emotion recognition to monitor and**

**assess the emotional states of their**

**workforce.**



<a name="br3"></a> 

OBJECTIVE

1 **Train traditional machine learning**

**models to classify facial emotions**

**Train a convolutional neural**

**network to classify facial emotions**

2

3

**Compare results**



<a name="br4"></a> 

D ATA

**Fer2013 Dataset:**

**A collection of 35887 labeled images of people’s facial expressions.**

Source: https://www.kaggle.com/datasets/ashishpatel26/facial-expression-recognitionferchallenge/data



<a name="br5"></a> 

D ATA

48 x 48 pixels = 2304 features

Source: https://www.kaggle.com/datasets/ashishpatel26/facial-expression-recognitionferchallenge/data



<a name="br6"></a> 

PRINCIPAL COMPONENT ANALYSIS

253 Feature

2304 Feature



<a name="br7"></a> 

DECISION TREE CLASSIFIER

DecisionTree Classifier is choosen as base model because it can do multi-label classification.



<a name="br8"></a> 

RANDOM FOREST CLASSIFIER

Random Forest is another machine learning algorithm that can do multi-label classification.



<a name="br9"></a> 

SVM CLASSIFIER

Sklearn’s SVM algorithm supports multi-label classification.



<a name="br10"></a> 

CONVOLUTIONAL NEURAL NETWORK



<a name="br11"></a> 

CONVOLUTIONAL NEURAL NETWORK



<a name="br12"></a> 

CONVOLUTIONAL NEURAL NETWORK

The neural work seems to overwhelmingly predict emotion to be "happy" which happens to

be the class with the highest number of samples.



<a name="br13"></a> 

CHALLENGES

Dataset is imbalanced, some emotions have too little sample. Upsampling

the dataset doesn’t improve accuracy.

1

Increase accuracy of convolutional neural network without over-fitting.

2



<a name="br14"></a> 

CONCLUSIONS

**Traditional machine learning algorithms like support Vector Machine**

**achieves better result than Convolutional neural network for facial**

**emotion recognition.**



<a name="br15"></a> 

NEXT STEP

**We can try other neural network architectures such as Transfer**

**Learning, VGGnet, Residual Network to achieve more accurate**

**predictions.**



<a name="br16"></a> 

**Thank You!**

