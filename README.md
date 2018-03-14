# image_classifier_with_CNNs
A small machine vision project I did which uses Conventional Neural Networks (CNNs) to cluster images 

Notes on data inputs:

- Images have been replaced with public images due to private NDA. Source code remains the same though model performance results / optimization parameters will obviously differ because of differing input data.

- I used the 'Bulk Image Downloaded' chrome pluggin (https://chrome.google.com/webstore/detail/bulk-image-downloader/lamfengpphafgjdgacmmnpakdphmjlji) to download a couple of hundred images of Big Ben and the Taj Mahal but you can use whatever you want!)

Instructions:

1- If you want to use your own images, make sure to delete the current contents of 'training_images' and replace it with your own images 
2- Then open 'CNN_cluster_model.ipynb' (Jupyter notebook) file and run the code! 
3- Cluster outputs will be saved in 'training_images/imagecluster'
4- Enjoy. Comments and feedback welcome! 

Further Optimization notes:

- If you want to further optimize this clustering algoirthm then play around with the 'sim' variable which controls the similairty level cutoff for the reduced images. Please remember to split your data into training/validation/testing sets if you do this (using the training set to train the model, the validation set to optimize similarity threshold, and final testing set to check performance metrics... otherwise the model will likely become overfit to your training set). Thanks. 
