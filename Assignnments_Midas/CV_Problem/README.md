1- The training of data is done on Google Colaborator.<br/>
2- For training model used is CNN<br/>

<b>CNN:</b><br/>
Deep learning CNN models to train and test, each input image will pass it through 
a series of convolution layers with filters (Kernals), Pooling, fully connected layers (FC) and 
apply Softmax function to classify an object with probabilistic values between 0 and 1.<br/>
Convolution of an image with different filters performs operations such as 
edge detection, blur and sharpen by applying filters.

<b>Summary:</b><br/>
1-Provide input image into convolution layer<br/>
2-Choose parameters, apply filters with strides, padding if requires. Perform convolution on the image and apply ReLU activation to the matrix.<br/>
3-Perform pooling to reduce dimensionality size<br/>
4-Add as many convolutional layers until satisfied<br/>
5-Flatten the output and feed into a fully connected layer (FC Layer)<br/>
6-Output the class using an activation function (Logistic Regression with cost functions) and classifies images.<br/>
