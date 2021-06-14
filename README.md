# Gesture_Recognition
### Problem statement: 
To create a deep learning model that can explain the content of an image in the form of speech through caption generation with the attention mechanism on the Flickr8K data set 
This type of model is a use case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text-to-speech library.This problem statement is an application of both deep learning and natural language processing. The features of an image will be extracted by the CNN-based encoder, and this will be decoded by an RNN model.

### Project pipeline:

The project pipeline can be briefly summarised in the following four steps:

* Data understanding: Load the data and understand the representation.
* Data preprocessing: In this step, we processed both images and captions in the desired format.
* Train/Test split: Images and captions are combined together to create the train and test data sets.
* Model building: The image captioning model is built by building the Encoder, Attention and Decoder model
* Model evaluation: The model was evaluated using the BLEU score.
