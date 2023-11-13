# Gunshots_in_Amazonia
Gunshots in Amazonia: Turning Sound into Images for use with Convolutional Neural Networks

## Project Overview

The "Gunshots in Amazonia" project is aimed at classifying gunshots from background Amazon forest sounds. Its primary objective is to contribute to the preservation of the Amazon rainforest by identifying illegal gunshots from audio recordings in protected areas. This initiative seeks to combat overhunting and illegal poaching, which pose a significant threat to the Amazon's unique biodiversity.

## Project Structure

This repository contains five Jupyter Notebook Python codes, each serving a specific purpose in the project:

### 1. 00_Proof_of_Concept
   - In this notebook, we explore the feasibility of the project, laying the foundation for the subsequent steps.

### 2. 01_Preprocessing_Gunshots
   - This notebook focuses on feature extraction and the transformation of audio data into a 3-channel 'image,' making it suitable for input into convolutional neural networks (CNNs).

### 3. 02_Split_wav_duration
   - Contains code for splitting audio files into equal segments for preprocessing, ensuring uniform input for the model.

### 4. 03_OC-SVM
   - This notebook introduces a One-class Support Vector Machine (OC-SVM), a machine learning algorithm used to establish further ground truth and increase the robustness of the model.

### 5. 04_Training CNN for gunshot classification
   - This is the training phase of the project. It employs the features extracted in notebook 01 and utilizes a convolutional neural network model to classify gunshots from the prepared audio data.

## Acknowledgements

I would like to express my gratitude to the following individuals and organizations for their valuable contributions to this project:

- Lydia Katsis
- Andrew Hill
- Evelyn Piña-Covarrubias
- Peter Prince
- Alex Rogers
- C. Patrick Doncaster
- Jake Snaddon

Their generous provision of a supplementary dataset significantly enriched the depth and diversity of this study.

I extend my thanks to Mendeley Data for hosting the supplementary dataset and providing a reliable platform that facilitated seamless access to critical research resources.

I am also thankful to the University of Suffolk for fostering an environment that nurtures academic exploration and innovation. The opportunity to undertake this research and share its findings is a testament to the University's commitment to excellence.
