# Fine-Tuned HuggingFace Classifier Model

## Description
This repository contains a Jupyter Notebook file containing a fine-tuned pretrained distillbert-base-uncased model from HuggingFace, trained to perform the task of sentiment analysis and classification of text into four categories: anger, joy, sadness and optimism. I trained the model on the CardiffNLP tweet_eval dataset. The project presented in this repository is a GitHub adaptation of a project I did as an assignment for the Lab sessions of the Statistical Language Processing course taught by Prof. Erhard Hinrichs and Dr. Marie Hinrichs at the University of Tübingen in the Summer Semester of 2023.

## Manual
I highly recommend running the file in Google Colab, as it was created using Google Colab. It is, however, adapted for the use with local resources, with some alternative blocks of code meant to be run on user's local resources. In case of running the file in a local Jupyter Notebook, I recommend to have NVIDIA CUDA toolkit configured in order to run the training on GPU. It is possible to run the training on CPU too, but it is going to take at least one eternity.

I plan to release the repository in the form of a standard Python project in the near future too.
