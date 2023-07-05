# Image_Classification - Scalp Image Classification for hair loss symtom detection.   
input: Korean Scalp Image (AI-hub)  
output: 4 classes  
  0: No hair loss  
  1: Minimal hair loss  
  2: Noticeable hair loss  
  3: Significant hair loss  

## Model  
Model: DenseNet4 w/ Pytorch  
Model Selection based on Accuracy among DenseNet-121(77.17%) & Lenet style CNN(75.17%) & ResNet50(73.95%)  
Best Accuracy: 77.17%  

## Settings:  
image Size: 256, 256  
batch size: 16  
learning rate: 0.001  
Cost Function: Cross Entropy  
optimizer: Adam  
