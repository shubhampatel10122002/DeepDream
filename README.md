# DeepDream
In DeepDream, the paper claims that you can follow the gradient to maximize an energy with respect to the input in order to visualize the input. I have implemented a Deep Dream-like image generation technique using a VGG13 neural network. 

Here we start with a random noise image and use gradient ascent to modify the image to maximize the model's confidence in specific target classes. The process iteratively modifies the input image by following the gradients that increase the activation of chosen class labels in the network.


https://github.com/user-attachments/assets/bd02a319-0984-4e9f-9ccf-0bfeb254ba9b

