# EEG Classifier based on DEAP database

## This repo only include code to proceed DEAP data, no data from DEAP contained!

For access of DEAP dataset, please sign EULA and send a request to DEAP team: http://www.eecs.qmul.ac.uk/mmv/datasets/deap/download.html

## Dependency
* python >= 3.5
* numpy
* pyEEG: https://github.com/forrestbao/pyeeg, need manual fix of source code, refers to issue: https://github.com/forrestbao/pyeeg/issues/26
* scikit-learn
* tensorflow-gpu

## ERD/ERS analysis
Fast Fourier Transformation:
* Windows size = 2 sec
* Windows step = 0.125 sec

## Model attempted
* Support Vector Machine
* Adaboost
* Random Forest
* Artificial neural network

## Best AC rate of Classification on Arousal, Valence, Domaince, Like dimension
* Arousal/Not: 82.6%
* Valence/Not: 83.6%
* Domaince/Not: 81.9%
* Like/Not: 85.1%
