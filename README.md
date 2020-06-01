# Classifying Food Images using Deep Learning

## Executive Summary
A certain image does not only necessarily represent a single attribute and most of the time it represents more than two. In other words, there can be multiple titles or labels that can be given for a single image. This problem is called multi-label classification which is used for content retrieval and scene understanding among few. For this study, a multi label classification algorithm is applied on food images using Keras (with Tensorflow backend). A simple CNN model is altered to give way to multi label classification. To make things easier, pre-trained CNN models are used particularly ResNet50, MobileNet, DenseNet121, and Xception. Afterwards, comparison of these results shall be done with Nanonets Multi Label Classification API. The results show a better F1 score at 75.06% for Nanonets and only about 70.46% for Xception model. Both of these models can be used for deployment as they both display intuitive and sound results.

## Guide to the Repository
This project contains two parts which are the jupyter notebook and the web application. The jupyter notebook contains the detailed methodology as well as my personal insights on the project. This repository also contains the web application where the user of the app can upload images which can predict possible labels for the certain image. The web application is deployable using Flask.

## Motivation
When we see certain food images, are they easy to describe? Sometimes yes, sometimes no. Because of this, I want to explore if Deep Learning can help me with classifying food images. Using the sample food images data gathered from the blog "How To Easily Classify Food Using Deep Learning and Tensorflow", I shall run pre-trained CNN models to predict labels for a particular food image. Given a food item, I would like to know what are the possible labels for a certain food image. For instance, given an image of a beef, the model shall provide tag such as "meat", "protein". This model can be useful for content based retrieval for businesses especially for the food industry where automated dietary plan app can be made based on user requirements. The use of this model comes in by automatically retrieving relevant images for the specific food item.


