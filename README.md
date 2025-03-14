Noisy Digit Image Segmentation and Evaluation

Overview

This project involves preprocessing, segmenting, and evaluating noisy single-digit CAPTCHA images. Various image processing techniques are applied to enhance image quality, followed by segmentation using different algorithms. The segmented results are then compared against ground truth masks using evaluation metrics.

Project Structure

.
├── Original_Images/             # Directory containing original noisy digit images
├── Ground_Truth_Images/         # Directory containing ground truth segmentation masks
├── Captcha.ipynb       		  # Main Python script jupyter notebook file for image processing and segmentation
├── README.md                    # Project documentation

Dependencies

Ensure you have the following libraries installed:

pip install opencv-python numpy matplotlib scikit-image scikit-learn

Image Processing Techniques

Filtering Methods:

Gaussian Blur

Bilateral Filtering

CLAHE (Contrast Limited Adaptive Histogram Equalization)

Segmentation Methods:

K-Means Clustering

Graph-Based Felzenszwalb Segmentation

Seed-Based Region Growing

Evaluation Metrics

To measure segmentation performance, the following metrics are used:

Intersection over Union (IoU)

Dice Coefficient

Pixel Accuracy

Execution Instructions

Upload this file along with Original_Images folder and Ground_Truth_Images folder into Jupyter Notebook

Then run each cell in Captcha.ipynb file one by one from top to bottom.

This will:

Load and apply filtering techniques to enhance the images.

Perform segmentation using multiple techniques.

Compare the segmented images with ground truth masks.

Display evaluation scores and generate visualizations.

Results & Visualization

The script will display:

Filtered and segmented images.

Comparison between ground truth and segmentation output.

IoU, Dice, and Accuracy scores in tabular and graphical formats.

Average Performance Metrics

The script computes and prints average evaluation scores:

Average IoU Score: 0.8640
Average Dice Coefficient: 0.9259
Average Pixel Accuracy: 0.8993

Future Improvements

Use deep learning-based segmentation models (U-Net, Mask R-CNN)

Improve noise reduction with advanced denoising techniques

Automate hyperparameter tuning for segmentation models

Contact

For any inquiries, please contact nandanyennam@gmail.com.