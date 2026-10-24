# hackathon-final-project
The final project for Mansoura Robotics' Hackathon 9.0 Advanced AI track. It is a CNN computer vision model trained on GTSRB dataset.
# Problem
Benchmark models based on their image recognition capabilities.
# Dataset
For this problem, we used the public [German Traffic Sign Recognition Benchmark (GTSRB)](https://docs.pytorch.org/vision/stable/generated/torchvision.datasets.GTSRB.html#torchvision.datasets.GTSRB) dataset which is available for direct download using 
```
torchvision.datasets.GTSRB(root="./data", download=True
```
# Architecture
The architecture of the model is a CNN sequential model with features: Convolutional layer 1 -> Batch normalization 1 -> ReLU activation 1 -> Max pooling 1 -> Convolutional layer 2 -> Batch normalization 2 -> ReLU activation 2 -> Max pooling 2 -> dropout and classifier: Linear 1 -> ReLU activation 1 -> Linear 2 -> ReLU activation 2 -> Linear 3

# Results
The model's final accuracy was 90.97% with the following loss curve figure: 
<img width="1694" height="938" alt="image" src="https://github.com/user-attachments/assets/c2c34f88-f263-4e64-80de-f659ad8c0b84" />
# How to run
1. Import all the necessary libraries from requirements.txt.
2. Make sure you have a network connection for the data download.
3. Open and run the notebook in your text editor / IDE of choice (Visual Studio Code, JetBrains PyCharm, Spyder, etc.).
4. Watch the magic happen.
