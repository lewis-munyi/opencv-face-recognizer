### Info
Contains the output pickle files which include:
1. **embeddings.pickle :** A serialized facial embeddings file. Embeddings have been computed for every face in the dataset and are stored in this file.
2. **le.pickle :** Our label encoder. Contains the name labels for the people that our model can recognize.
3. **recognizer.pickle** : Our Linear Support Vector Machine (SVM) model. This is a machine learning model rather than a deep learning model and it is responsible for actually recognizing faces.
 
 
 All these files will be autogenerated when we train the algorithm.