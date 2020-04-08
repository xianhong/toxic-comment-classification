### Multi-label Classification of toxic comments (Kaggle's competition dataset)  using pretrained Google BERT model 
 * `keras-bert.ipynb`: Fine tune a multi-label classifier on top of Google's BERT model (fixing its parameters).\
    Use Hamming loss together with a custom defined recall metric (measuring the proportion of positive labels being correctly predicted by the classifer) to evaluate the performance of the classifier.

 * `use-model.ipynb`: Use fine-tuned multi-label classifier for prediction
