# Celebrity-Face-Match
A self project which determines which bollywood celebrity closely resembles you.

This Streamlit app predicts which Bollywood celebrity your uploaded image resembles based on facial features. It uses a pre-trained VGGFace model for feature extraction and MTCNN for face detection.

Features
 1. Face Detection: Utilizes MTCNN (Multi-task Cascaded Convolutional Neural Networks) to detect faces in the uploaded image.
 2. Feature Extraction: Extracts facial features using a pre-trained VGGFace model (ResNet50) with average pooling.
 3. Celebrity Prediction: Computes cosine similarity between the extracted features and precomputed feature embeddings of Bollywood celebrities to recommend the closest match.
 4. Interactive Web Interface: Built with Streamlit, allowing users to upload an image and instantly see the predicted celebrity match.
