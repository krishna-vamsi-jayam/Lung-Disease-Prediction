# Lung-Disease-Prediction
  Each year, pneumonia claims about one million victims globally. In general, the risk is most severe for children, though there are regional disparities as well. 
One of the most urgent needs in combatting pneumonia is a cost-effective manner of diagnosing X-ray images. Current methods require highly skilled personnel and are impractical for many regions of the world.

   The doctor, when interpreting the chest x-ray, will look for white patches in the lungs to detect pneumonia. However, such hazy patterns would also be observed tuberculosis and severe cases of bronchitis. For the purpose of conclusive diagnosis, the purpose of this study is to identify pneumonia, through analysis of chest X-ray images, to recognize patterns of the disease using a neural network.

  Main principle is to predict whether the child is having Pneumonia or not. For this prediction we have to train our model with most accuracy so that it can study each and every pixel of the image clearly. Transfer Learning has many features to process the images and predict the output.

Since the dataset is an image dataset consists of X-Rays it is huge in size. so please find the dataset at https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia.
I've worked in Google Colab so the data input paths may differ please change the path before reading the images.

I've created a model using VGG16 Algorithm and trained it using the "train" dataset and later allowed the model to asses itiself using the "test" dataset. once the results were obtained wth higher accuracy i have exported that model.

In the full trained model i've used "val" dataset to predict the presence of disease.

