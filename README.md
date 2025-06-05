# Randomforestrepo

Osteoporosis Diagnosis Using Machine Learning and Deep Learning
# Overview
This is my research project focused on diagnosing osteoporosis using Machine Learning (ML) and Deep Learning (DL) techniques.

The objective is to replace the conventional DXA scan method with Cone-Beam Computed Tomography (CBCT) scans, which are more accessible and cost-effective. By leveraging advanced ML/DL algorithms, this project aims to enable accurate and scalable osteoporosis screening.

# Project Description
  Data Source: CBCT (Cone-Beam Computed Tomography) scans

  Goal: Predict T-scores for three key subregions of bone:

   Cortical bone

   Trabecular bone

   Spinal axis

# Machine Learning Workflow
Feature Engineering:

Extracted radiomic features from CBCT scan images.

Performed feature selection to reduce dimensionality and enhance model performance.

## Modeling:

Trained a Random Forest Regressor to predict T-scores.

Used K-Fold Cross-Validation to assess model generalizability and avoid overfitting.

Applied randomization and shuffling during training to ensure robustness.

Evaluated performance using RMSE, MAE, and R² metrics.

Current Deep Learning Work
Transitioning to image-based training using Convolutional Neural Networks (CNNs).

Preparing datasets by:

Normalizing and resizing input CBCT image slices.

Designing CNN architectures to directly learn from imaging data for improved T-score prediction.

Next Steps
Complete CNN training and compare with traditional ML results.

Experiment with transfer learning using pre-trained models (e.g., ResNet, VGG).

Integrate an explainability component (e.g., Grad-CAM) to visualize important regions in diagnosis.

Tools & Libraries Used
Python (NumPy, Pandas, Matplotlib, Scikit-learn)

TensorFlow / PyTorch (for CNN implementation)

OpenCV & SimpleITK (for image processing)

Jupyter Notebooks for experimentation and documentation

Author
Samrakshyan Adhikari
Undergraduate Research Assistant
Electrical Engineering Major, Texas State University
Email: [YourEmail@txstate.edu]

 
