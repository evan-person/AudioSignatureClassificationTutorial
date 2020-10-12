# KerasTutorialMLcourse

## Introduction
This notebook is a tutorial on using Keras to develop a model for classifying sound files as cat or dog noises. It walks the reader through the steps of loading and augmenting data, designing and fitting a model, and evaluating the model using test data.

## Team
Vishal Devnale, Vasishtha Sohani, Evan Lucas

## Project Outline

Project was performed in Google Colaboratory for ease of collaboration. 

Audio files are transformed into 2D space by use of a mel-spectrogram. This was either windowed or padded as needed to meet a fixed time length. This is fed into a convolutional neural network that is similar to an image identification one. It has two 2D convolutional layers, followed by a max pooling layer and a dropout layer, which is repeated before going into dense layers. 

For fun, we had some friends record themselves pretending to be dogs or cats and tried classifying them using the model as well. The results of these are included at the end of the document.

## Future improvements
This could be extended by providing a null class, so that there was a third option for neither a cat nor a dog. It could be further extended with other classes of noises as well. Other methods for bringing in sound files should also be explored, but that would be an entirely separate project.


