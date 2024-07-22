
# AI Capstone Project: Crack Detection in Buildings

## Table Content
1. Dataset Overview
    - Important note
    - Dataset Details
    - Challenges
2. Project Overview
3. Conclustion
3. Credits

## 1. Dataset Overview
The dataset used in this project is Concrete Crack Images for Classification, sourced from Mendeley.com. We would like to extend our gratitude to the authors for their valuable contribution.

### Importance of Crack Detection:
Crack detection is crucial for the structural health monitoring and inspection of buildings. Identifying cracks early helps in preventing potential structural failures and ensures the safety and longevity of buildings.

### Dataset Details:
1. Data Type
- Classes:Cracked concrete (positive tensor)
- No cracks (negative tensor)
2. Data details
- Total Images: 40,000 RGB (color) images
- 20,000 images with cracks
- 20,000 images without cracks
3. Data Split:
- 75% for training
- 25% for validation

### Challenges Associated with the Dataset
Noise and Background Texture: Cracks can be confused with noise in the background.
Foreign Objects: Objects in the images can obscure or mimic cracks.
Illumination Variations: Inhomogeneous lighting can affect crack visibility.
Irregularities: Exposure of jointing and other irregularities can complicate detection.

## 2. Project Overview
**Steps Involved**
1. Data Acquisition: Obtain the dataset from object storage (Skills Network Lab).
2. Data Pre-processing: Prepare the data for model training.
3. Feature Extraction: Convert images to vectors.
    Use a linear classifier initially.
4. Model Training:
- Utilize pre-trained models with state-of-the-art architectures.
- These models are trained on large datasets by experts using powerful GPUs.
- This projct focus on using these pre-trained networks and modify the output layer to suit our dataset.
5. Model Customization:
Change the output layer of the network.
- Train the modified network on our dataset.
- Prediction:
    Use the trained network to make predictions on new data.
    Pre-trained Models
    Instead of building our own network, we leverage pre-trained networks that have been trained on vast amounts of data. This allows us to:

## 3. Conclusion
This project demonstrates how to use deep learning for crack detection in buildings, emphasizing the importance of structural health monitoring. 


## 4. Credits
This project is part of the IBM AI capstone project. Special thanks to IBM for providing the resources and support necessary to complete this project.