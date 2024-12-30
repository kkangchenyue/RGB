Model Overview
Feature Extraction:
This part consists of five convolutional layers that are responsible for extracting useful features from the input image. Convolutional layers help in identifying local patterns or features in the image such as edges, textures, etc.
Each convolutional layer uses a filter (also known as a convolutional kernel) to extract different features from the input image.
After each convolutional layer, there are activation functions (e.g. ReLU) and pooling layers (e.g. Maximum Pooling) which help to reduce the spatial dimensions of the feature maps and improve the robustness of the extracted features.

Feature Mapping:
In the feature mapping stage, the high-dimensional feature maps generated by the convolutional layers are flattened into low-dimensional one-dimensional vectors, which are then used for the final concentration prediction.
This phase usually consists of fully connected (FC) layers. The feature vectors are mapped into a one-dimensional space through five fully connected layers.
The final fully connected layer output represents a single value for the predicted concentration of methotrexate. 
Below are all the image data
![image](https://github.com/user-attachments/assets/d5bbb931-cb8e-450a-b00a-e73a564a05f3)
![image](https://github.com/user-attachments/assets/c8c7ef08-d8d6-4445-b8ac-4d05d2d753b6)
![image](https://github.com/user-attachments/assets/f2c5cd56-df09-4dbc-a4ee-59e63974ea67)
