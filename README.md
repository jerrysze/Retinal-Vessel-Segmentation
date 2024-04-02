# Retinal-Vessel-Segmentation

Task 1: Contrast Sretching

Retinal images are low-contrast images. In other words, the intensities of the vessels do not stand out by a large margin compared to the background. 

As such, I will enhance the retinal images by stretching their contrast.
I will use the following contrast stretching formula:

I𝑛𝑒𝑤 = (I − I𝑚𝑖𝑛)/(I𝑚𝑎𝑥 − I𝑚𝑖𝑛) ×255 , where I is the current pixel intensity value

I𝑚𝑖𝑛  is the minimum intensity value present in the whole image 

I𝑚𝑎𝑥  is the maximum intensity value present in the whole image 

I𝑛𝑒𝑤  is the new output intensity value.


Task 2: Image Rescaling
Our contrast-enhanced data arrays x_train_enhanced and x_val_enhanced are arrays in the range of  [0,255]. 
Need to standardize the input by rescaling the pixel values to  [0,1].

I will build a special type of CNN model called the Autoencoder to perform automatic segmentation of retinal vessels.

Task 3: Build the autoencoder model

Task 4: Compile the model

Task 5: Train the model

Task 6: Predict the segmentation masks

Task 7: Mask thresholding

Task 8: Implementing Dice coefficient

Task 9: Calculating the average dice
