# Toxic Comment Classifier
Submission for Advanced ML project (Silky and Rahim)

This project introduces various deep learning approaches applied to the task of classifying toxic messages. In particular, we attempt to use the Naive-Bayes model, Multi-Perceptron Model and Long-Short Term Memory networks to identify toxicity in online messages. We evaluated our approaches on Wikipedia comments from the Kaggle Toxic Comments Classification Challenge 2 dataset.  In addition to correctly classifying toxic messages, the project also attempts to identify and control for some of the identity biases that arise in labelling comments as toxic. Our assessment found that our forward LSTM model achieved the best performance on binary classification. Though best, the model does not perform as good as we had expected. It is only marginally better than the Naive Bayes model.

In this repository, we have added the pipeline for the baseline models including naive bayes a well as deep learning ones. Following are the descriptions for the files:

1. final_project_lstm_sa-f1_included.ipynb: This file contains the final versios of Type 1 and Type 3 LSTM models specified in the report
2. SingleLayer_Perceptron: This file contains Single layer neural network with GloVe embeddings
3. final_project_lstm_sa-f1_included_keepstopwords.ipynb: This file contains the final versions of Type 5 LSTM model specified in the report with stop words retained
4. final_project_lstm_sa-f1_included_keepstopwords_undersampling.ipynb: This file contains the LSTM Type 6 model with undersampling based on sample (identity) weights and a dropout layer. 
5. final_project_lstm_sa-f1_included_keepstopwords_undersampling2-classweight.ipynb: This file contains the LSTM Type 7 model with undersampling based on class weights and a dropout layer.
6. final_project_lstm_sa_bk.ipynb: This file contains the Type 1, 2, 3 ad 4 LSTM model trial attempts made in tbe beginning of the project. This is not a very clean code and most of the lines may have been commented out that were previosuly run as we were trying multiple variations. 
7. MultiLayer_Perceptron: This includes a 3 layer NN model with GloVe embeddings
8. final_project_sa: The file contains the data exploration work as well as the Naive Bayes model
