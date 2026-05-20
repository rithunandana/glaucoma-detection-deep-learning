# Glaucoma Detection Using Deep Learning

## Overview
This project focuses on the automated detection of glaucoma from retinal fundus images using deep learning techniques. Glaucoma is a serious eye disease that can lead to permanent vision loss if not detected early. The goal of this project is to build an intelligent diagnostic model that assists in early glaucoma screening using image classification.

## Features
- Automated glaucoma detection from retinal fundus images
- Image preprocessing and enhancement
- Deep learning-based classification model
- Model performance evaluation using standard metrics
- Visualization of training performance and prediction results

## Dataset
This project uses the **ACRIMA (Automatic Classification of Retinal Images for Glaucoma Assessment)** dataset, which contains retinal fundus images categorized into:
- Glaucoma
- Normal

> Note: Dataset is not included in this repository due to size limitations.

## Technologies Used
- Python
- Jupyter Notebook
- TensorFlow / Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-learn

## Project Structure
``` id="8f39dv"
Glaucoma-Detection/
│
├── Glaucoma_Detection_ACRIMA.ipynb   # Main notebook
├── README.md                         # Project documentation
├── requirements.txt                  # Required dependencies
├── images/                           # Sample outputs/screenshots
└── dataset/                          # Dataset folder (not uploaded)
```

## Installation

### Clone the Repository
```bash id="y5kpjc"
git clone https://github.com/yourusername/glaucoma-detection.git
cd glaucoma-detection
```

### Create Virtual Environment (Optional)
```bash id="kr9f0r"
python -m venv venv
```

Activate environment:

Windows:
```bash id="vhrw8e"
venv\Scripts\activate
```

Mac/Linux:
```bash id="7wjlwm"
source venv/bin/activate
```

### Install Dependencies
```bash id="6s5d7o"
pip install -r requirements.txt
```

## Usage
1. Download the ACRIMA dataset.
2. Place the dataset in the `dataset/` folder.
3. Open the Jupyter Notebook:
```bash id="e7g6ie"
jupyter notebook
```
4. Run `Glaucoma_Detection_ACRIMA.ipynb` step by step.

## Model Workflow
- Load retinal fundus image dataset
- Preprocess and resize images
- Normalize pixel values
- Split data into training and testing sets
- Build deep learning classification model
- Train model on retinal images
- Evaluate performance
- Predict glaucoma presence on unseen images

## Evaluation Metrics
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Sample Output
Example predictions:
- Normal Eye
- Glaucoma Detected



## Future Improvements
- Deploy as a web application
- Improve model accuracy with transfer learning
- Add Grad-CAM visualization for explainability
- Extend to multiclass eye disease detection

## Author
**Rithu Nandana**

