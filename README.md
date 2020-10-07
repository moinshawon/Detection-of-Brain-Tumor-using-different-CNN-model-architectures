Our primary purpose is to detect tumor tissue at an early stage. In this chapter,
we will try to discuss how we have built our model to detect the tumor. After
the collection of data, we did pre-processing where included image extraction, data
segmentation according to train, validation, and test. We divided our data into three
segments named train, test, and validation. In each segment, we created a ‘yes’ class
for the patient with a brain tumor and ‘no’ class for the patient having no tumor.
Then We took pre-trained CNN model VGG16, VGG19, inception V3, ResNet50,
DenseNet121, and Xception. We have built a Convolutional Neural Network as we
did not take the fully connected layer of the transfer model. After that, we start
training our model as well as checked the accuracy by validation dataset. Then we
did model testing and got different accuracy for different CNN models. At last, we
analyzed by plotting the accuracy and loss function 
