# Machine Learning Resources
Resource to get started with machine learning

Table of Contents
=================

  - [x] [Historical Perspective](#historical-perspective) 
  - [ ] [Review of basics](#review-of-basics)
      - [x] [Regression](#regression)
      - [x] [Classification](#classification)
      - [ ] [Support Vector Machine](#support-vector-machine)
          - [x] [As Classifier](#as-classifier)
          - [ ] [As Regressor](#as-regressor)
      - [ ] [Deep Neural Network](#deep-neural-network)
          - [x] [Intuition](#intuition)
          - [x] [Backpropagation in Detail](#backpropagation-in-detail)
      - [ ] [Convolutional Neural Network](#convolutional-neural-network)
      - [ ] [Recurrent Neural Network](#recurrent-neural-network)
  - [ ] [Optimizing Deep Learning](#optimizing-deep-learning)
  - [ ] [Generative Machine Learning](#generative-machine-learning)
  - [ ] [Domain Adaptation](#domain-adaptation)
  - [ ] [Meta Learning](#meta-learning)
  - [ ] [Incremental Learning](#incremental-learning)
  - [ ] [MISC](#misc)
  
  
Historical perspective
==========================

1. [A History of Machine Learning](https://cloud.withgoogle.com/build/data-analytics/explore-history-machine-learning/) - This beautiful blog post almost summarizes the entire history of machine learning to date.
2. [Deep Learning 101 - Part 1: History and Background](http://beamlab.org/deeplearning/2017/02/23/deep_learning_101_part1.html) - A more detailed history and background of machine learning by contrasting it with the recent developments.

Review of basics
====================

Regression
--------------------------
1. Andrew Ng Lectures - Linear Regression
    * Univariate - [1](https://youtu.be/kHwlB_j7Hkc?list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN), [2](https://www.youtube.com/watch?v=yuH4iRcggMw&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=5), [3](https://www.youtube.com/watch?v=yR2ipCoFvNo&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=6), [4](https://www.youtube.com/watch?v=0kns1gXLYg4&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=7), [5](https://www.youtube.com/watch?v=YovTqTY-PYY&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=9), [6](https://www.youtube.com/watch?v=YovTqTY-PYY&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=9), [7](https://www.youtube.com/watch?v=GtSf2T6Co80&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=10).
    * Multivariate - [1](https://www.youtube.com/watch?v=Q4GNLhRtZNc&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=18), [2](https://www.youtube.com/watch?v=pkJjoro-b5c&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=19), [3](https://www.youtube.com/watch?v=B-Ks01zR4HY&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=24).
2. [Linear Regression with Tensorflow*](https://www.guru99.com/linear-regression-tensorflow.html) - This blog post provides a overall idea of the concept of Linear Regression with a Tensorflow example.


Classification
-------------------------
1. Andrew Ng Lectures - Logistic Regression
    * Binary classification - [1](https://www.youtube.com/watch?v=-la3q9d7AKQ&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=32), [2](https://www.youtube.com/watch?v=t1IT5hZfS48&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=33), [3](https://www.youtube.com/watch?v=F_VG4LNjZZw&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=34), [4](https://www.youtube.com/watch?v=HIQlmHxI6-0&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=35), [5](https://www.youtube.com/watch?v=TTdcc21Ko9A&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=36).
    * Multi-class classification - [One vs All](https://www.youtube.com/watch?v=-EIfb6vFJzc&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN&index=38)

Support Vector Machine
-----------------------------
### As Classifier ###
>  _(Understand this before trying to attempt SVM as regressor)_ 

1. [Understanding Support Vector Machine algorithm from examples](https://www.analyticsvidhya.com/blog/2017/09/understaing-support-vector-machine-example-code/) - This blog provides a basic intuition about Support Vector Machine (SVM) as classifiers.
2. [MIT Lecture - Support Vector Machine](https://www.youtube.com/watch?v=_PwhiWxHK8o) - Get an intuition of SVM as classifier from the above blog source before proceeding with this. This lecture gives a detailed explanation of the internal workings of SVM as classifier.
3. [Siraj Raval Youtube Video - Support Vector Machine](https://www.youtube.com/watch?v=g8D5YL6cOSE) - This video contains a less elabaorate discussion about SVM as classfier with code

### As Regressor ###

Deep Neural Network
---------------------------

### Intuition ###
>  _(Gain a basic intuition of Deep Neural Networks before proceeding in detail about backpropagation)_ 

1. [Deep Neural Network Playlist by 3blue1brown](https://www.3blue1brown.com/neural-networks) - This playlist of videos provides the best possible intuition of Deep Neural Networks without much mathematical overload.
2. [Neural Network and Deep Learning blog by  Michael Nielsen](http://neuralnetworksanddeeplearning.com/) - This blog is the reference material behind the previously mentioned source. It provides a much more detailed idea of Deep Neural Network.
3. [Deep Learning Book by Ian Goodfellow](http://www.deeplearningbook.org/) - This is the go-to book for understanding Deep learning. I have mentioned this as 3rd resource as the size of the book is quite large. Other than that this is best possible study material for learning about Deep Neural Networks.

### Backpropagation in Detail ###

1. [Backpropagation - Standford Lecture](https://www.youtube.com/watch?v=d14TUNcbn1k) - This lecture gives a detailed idea about how backropagation works but doesn't explain it properly with respect to Deep Neural Network.

MISC
==================
* [Dropout](https://machinelearningmastery.com/dropout-for-regularizing-deep-neural-networks/)
    

_* I didn't find a blog which is more intuitive than this. I will add it if I find anything in the future._
