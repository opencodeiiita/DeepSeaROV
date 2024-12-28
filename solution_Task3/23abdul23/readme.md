I have tested 4 models using the same type of Architecure but with different set of tunings on parameters

Convonutional Layer , Learning Rate, No. of Neurons, 1st Droput Rate, 2nd Dropout Rate, ----> train_accuracy
1. 512 , 0.0005, 1500, 0.25, 0.4 ----> 0.28
2. 1024, 0.0001 , 1800, 0.3, 0.35 ----> 0.37

After this I have used train_augmented as the training set, where using the augmented functions I have generaed more images for training

3. 1024, 0.0001, 1800, 0.3, 0.35 , train augmented ----> 0.71
4. 1024, 0.0001, 1900, 0.25, 0.4 , train augmented ----> 0.79

