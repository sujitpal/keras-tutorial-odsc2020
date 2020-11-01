# keras-tutorial-odsc2020

Colab Notebooks for my Keras Tutorial [Keras from Soup to Nuts](https://odsc.com/speakers/keras-from-soup-to-nuts-an-example-driven-tutorial/) presented at [ODSC West 2020](https://odsc.com/california/).

## Motivation

[Keras](https://keras.io/) was the first Deep Learning framework I used to build my own networks from scratch. I wrote a blog post about my introduction to Keras -- [Why I love Keras, and why you should too](https://opendatascience.com/why-i-love-keras-and-why-you-should-too/) explaining why I like the framework.

## Abstract

Keras, with its intuitive API, has traditionally been one of the easiest ways to get started with building Deep Learning models. In the past, this ease of use came with some major tradeoffs to flexibility. However, through the relentless efforts of its creator and user community, Keras has seen several face-lifts, and the need for tradeoffs have largely been eliminated. Not surprisingly, its one of the most popular platforms used for developing Deep Learning models today.

This workshop hopes to convince participants that Keras is a worthwhile addition to their Machine Learning toolbelt. It teaches them how to build their own Keras models, initially using components already available in Keras, then extend them by customizing some of these components, and finally exploit the underlying Tensorflow platform for maximum flexibility and performance. They will also be able to work with the many cool (sometimes SOTA) models shared by the Keras community.

## Session Outline

The notebooks are for a 3 hour training session, broken up into 3 parts of 45 mins (plus 15 minute break) each.

__Part I:__ Learn why Keras deserves your attention, get an example-driven overview of functionality Keras offers out of the box, and learn to use these building blocks to build your own deep learning classifier. Participants will learn how to build a Keras model by the end of this module.

__Part II:__ Continue your Keras journey by looking at ways by which you can simplify your code and make your network perform better, by utilizing advanced features of Keras. Also learn about ways in which you can customize and extend Keras. Participants will apply these learnings to improve the model they built in Part I.

__Part III:__ Take your Keras skills to the next level by learning how to take advantage of the underlying Tensorflow platform (take over the training loop with GradientTape, speed up computation with @tf.function, train your model using multiple GPUs and work with TPUs on Collab). Reference code illustrating these concepts will be provided. We will also provide pointers to Keras resources for participants to explore on their own after the tutorial.

## Table of Contents

* Part I
  * Machine Learning Basics
  * Keras Basics
  * Keras CNN Demo
  * Exercise 1 - CIFAR-10 classification with CNN
* Part II
  * Extending / Customizing Keras
    * Residual Connections
    * Custom Loss function (F1)
    * Custom callback (LR finder)
  * Transfer Learning
  * Exercise 2 -- use Data Augmentation and LR finder to improve TL results
* Part III
   * Keras for Sequence input
     * RNN
     * Word Embeddings
     * Transformers
   * Sequence to Sequence (+ attention)
   * Useful Tensorflow features
     * Tensorflow tf.data.Datasets
     * Customized training loops (tf.GradientTape)
     * Distributed trainingu

## Pre-requisites

Ability to program in Python. Some knowledge of Machine Learning and/or Deep Learning desired but not required.o

## Running the Notebooks

All the notebooks are runnable and have no external dependencies. You can use these notebooks one of three ways.

* Read them -- github can render Jupyter notebooks, so clicking on them should (in most cases, barring issues with github rendering) open the notebook in the browser. All notebooks have been saved with results, so you can see the results in the cell outputs.
* Run them using the [Run on Colab] button -- each notebook has this button, clicking it will open the notebook as a Colab notebook in your own Colab account.
* Run them individually using the [Colab Github Viewer](https://colab.research.google.com/github/). Bring the viewer up and copy paste the Github URL for the notebook.
* Download them locally or run them on Colab -- you can also clone the entire repository, and either run them locally or upload the notebooks to your Colab account and run them there. To do this, you will have to run `git clone git@github.com:sujitpal/keras-tutorial-odsc2020.git` (or equivalent GUI action) or download the repository as a zip file using the Github Desktop tool. You can then upload the notebooks individually to Colab and run them.

