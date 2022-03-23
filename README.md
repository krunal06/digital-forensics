# digital-forensics

I am using dataset available in kaggle to perform my experiments. It is first fetched by finalCNN_model and it performs deep learning approch to extract the featues of
an images. Feature extraction task is being done by final_features.py file. It will extract the last layer of the model and save the image features to .csv file with labels.

At last I have performed some experiments using random forest classifier on those features. Also, Last layer has 512 vector dimensions. So I have performed PCA and only 
kept top 60 features which are useful to classification process.

I have experimented svm and random forest classifiers on pca generated features also and got enhacnced accuracy than normal one.
All experiments are done in pca_rfc.pynb file.

Now, my goal is to identify file creator tool using deep learning and also meta data change of the documents for digital forensic purpose.
