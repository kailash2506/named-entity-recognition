# Named Entity Recognition

## AIM

To develop an LSTM-based model for recognizing the named entities in the text.

## Problem Statement and Dataset

we propose a deep neural network (NN) architecture, namely the bidirectional Long-Short Term Memory (Bi-LSTM) based model for NER. Based on existing gold standard datasets, we evaluated and compared several models for identifying biomedical named entities. Our deep NN based Bi-LSTM model using word and character level embeddings outperforms CRF and Bi-LSTM using only word level embeddings significantly.


![image](https://github.com/RoopakCS/named-entity-recognition/assets/139228922/96783a22-8833-4837-8f76-a39c9b995880)

## DESIGN STEPS

### STEP 1:
Import the necessary packages.

### STEP 2:
Load the dataset, and fill the null values using forward fill

### STEP 3:
Create a list of words, and tags. Also find the number of unique words and tags in the dataset.

### STEP 4:
Create a dictionary for the words and their Index values. Do the same for the tags as well.Train and test the dataset.

### STEP 5:
Perform padding the sequences to acheive the same length of input data.

### STEP 6:
Build a model using Input, Embedding, Bidirectional LSTM, Spatial Dropout, Time Distributed Dense Layers.

### STEP 7:
Compile the model and fit the train sets and validation sets.

### STEP 8
Plot the necessary graphs for analysis. A custom prediction is done to test the model manually.

## PROGRAM

Include your code here

## OUTPUT

### Training Loss, Validation Loss Vs Iteration Plot

![image](https://github.com/kailash2506/named-entity-recognition/assets/149034874/ee872843-f8da-444f-907c-395bced20acc)

![image](https://github.com/kailash2506/named-entity-recognition/assets/149034874/e33ea6ef-3d7d-4929-974e-d0801fdbd2ea)


### Sample Text Prediction
![image](https://github.com/kailash2506/named-entity-recognition/assets/149034874/398c8ab2-9d38-485b-96d7-e482c6bc2f16)


## RESULT
Thus, an LSTM-based model for recognizing the named entities in the text is developed.
