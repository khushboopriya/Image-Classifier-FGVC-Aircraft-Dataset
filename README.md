#Pytorch Code for Resnet model

Overall Steps :
 1. Created a dictionary with keys as variants and value as family, with help of indexes of images 
 2. Since each row of variant.txt represents each file just in order of files in train folder, I created a list of families which denotes family of each folder in train data.
 3. For that I have created 2 notebooks , one is for creating test, train and val dataset from the given folder, named data creation in format that it can be trained on resnet i.e, the folder train,test and val , all has folders in name of their family, and inside that lies pictures of that family with help of dictionary created.
Lastly I have trained model in modeltrainingandvalidation.ipynb file on 500 epochs

