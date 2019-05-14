# Caltech_101_object_classification
Object classification using the caltech101 dataset.

The code in this repository is inspired/copied by the repository https://github.com/fchollet/deep-learning-with-python-notebooks that has the code from book "Deep Learning with Python".

More specifically, I am running code from the notebooks:
https://github.com/fchollet/deep-learning-with-python-notebooks/blob/master/5.2-using-convnets-with-small-datasets.ipynb
https://github.com/fchollet/deep-learning-with-python-notebooks/blob/master/5.3-using-a-pretrained-convnet.ipynb
adapted to the Caltech101 dataset. Please refer to the original Jupyter Notebooks above for further information.

## Depedencies
  - python >= 3.6
  - numpy
  - matplotlib
  - openCV
  - tensorflow >= 1.9
  - keras >= 2.2
 
The code in this repository needs to run on a machine has has a Cuda capable GPU installed along with the respective CUda drivers and CuDNN. It has been tested on Linux Ubuntu 16.04 using Anaconda 3 virtual environment.

## Explanation of files

  - **get_dataset.sh** : downloads and untars the dataset. Please run it once.
  - **\*.h5** : saved trained Keras models. See next section for download.
  - **Caltech_101_split_dataset_and_first_NN.ipynb** : this notebooks splits the dataset into train and test. It also runs a first simple Neural Network for the classification.
  - **Caltech_101_pretained_convnet.ipynb** : training using pre-trained networks as features extractors and fine-tuning.

## Pre-trained models

If you would like to use the trained Keras models I produce you can download them from [here](https://mega.nz/#F!q24kjahL!xXGGSliq4u4pHINLbMcSYw).
