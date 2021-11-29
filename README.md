# GTSRB-German-Traffic-Sign-Recognition

In this project, I used Python and TensorFlow to classify traffic signs.

Dataset used: German Traffic Sign Dataset. This dataset has more than 50,000 images of 43 classes. 

I was able to reach a more than +95% validation accuracy, and a +95% testing accuracy.

I utilized deep neural networks and convolutional neural networks to classify traffic signs. I trained and validated a model so it can classify traffic sign images using the German Traffic Sign Dataset. After the model was trained, I tested out the model on images of German traffic signs I found on the web. The rubric contains "Stand Out Suggestions" for enhancing the project beyond the minimum requirements, of which I believe I accomplished by augmenting the training data and challenging my classifier with "toxic" difficult to read road signs.

The goal of this project was to build a Convolutional Neural Network (CNN) in TensorFlow and Python.






## Dependencies

This are the main packages used:

 - [Numpy](https://numpy.org/)
 - [Tensorflow](https://www.tensorflow.org/api_docs/python/tf/math/tan)
 - [Python 3.5 or above](https://www.python.org/) 
 
Full details on the requirements.txt file.  
## Conclusion

This App was very effective during the experimentations. In the end, the traffic sign classifier App works pretty well overall with the testing time.

However, the App some time did not work as good with ramdom sample images from the internet.

Moreover, if a self-driving car needs to find traffic signs in public, it first needs to know where the traffic signs are. For speeding signs, we may need an OCR (object recognition) mechanism that scan across the image with sliding windows to find the candidate signs. This kind of detection mechanism is not covered in this App project. 
