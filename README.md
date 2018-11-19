# Gramener--Product-Team-Intern-ML
Devanagari image classification 
1.	Analysis of the data set.
  •	The Train data folder consists of 46 folders which contains similar image with different shifts.
  •	The images are related to Devanagari Hand written images.
  •	The train data set contains 78200 images which are categorized by 46 classes.
  •	The images are in .PNG format and the size 32 X 32.
2.	Extract the each folder name as the label name.
3.	Reshape the image size to fit into the model.
4.	For images CNN works well so I tried first with CNN.
5.	Built the CNN architecture with the bellow hyper parameters.
  •	6 Convolution layers ( activation function = relu)
  •	3 Pooling layers.
  •	Flattening
  •	Added dense layer for the output(activation function = softmax)
  •	Learning rate = 0.001
  •	Momentum = 0.9
  •	Optimizer = SGD
  •	Loss function = Categorical_cross entropy
  •	Error metric = accuracy
  •	Ephochs = 5
  •	Batchs = 32
6.	Fit the model on Train images and for validation test images
