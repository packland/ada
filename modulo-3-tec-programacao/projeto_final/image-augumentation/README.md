#Gerador de imagens diferentes aleatório para machine learning (image augmentation)

Data augmentation is a process of artificially increasing the amount of data by generating new data points from existing data. This includes adding minor alterations to data or using machine learning models to generate new data points in the latent space of original data to amplify the dataset. 

Augmented data: Derived from original images with some sort of minor geometric transformations (such as flipping, translation, rotation, or the addition of noise) in order to increase the diversity of the training set.

##Augumentations

###Position Augmentation
-Center Crop: Crops the given image at the center. Size is the parameter given by the user.
-Random Crop: Crop the given image at a random location. 
-Random Vertical Flip: Vertically flips the given image randomly with a given probability. 
-Random Horizontal flip: Horizontally flip the given image randomly with a given probability. 
-Random Rotation: Rotate the image by some angle. 
-Resize: Resize the size of the input image to a given size. 
-Random Affine: Random affine transformation of the image keeping center invariant. 

###Color Augmentation
-Brightness: One way to augment is to change the brightness of the image. The resultant image becomes darker or lighter compared to the original one.
-Contrast: The contrast is defined as the degree of separation between the darkest and brightest areas of an image. The contrast of the image can also be changed.
-Saturation: Saturation is the separation between the colors of an image.

Referência: https://www.v7labs.com/blog/data-augmentation-guide