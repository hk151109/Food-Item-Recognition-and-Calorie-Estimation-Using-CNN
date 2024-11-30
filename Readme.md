# Food Item Recognition and Calorie Estimation Model

## Project Overview

This machine learning project develops an advanced system for recognizing food items from images and estimating their calorie content. By leveraging cutting-edge image classification techniques and nutrition APIs, users can easily track their dietary intake and make informed food choices.

## Features

- **Intelligent Image Classification**
  - Uses Convolutional Neural Network (CNN) to classify food items
  - Trained on the comprehensive Food-101 dataset
  - Supports recognition across 101 distinct food categories

- **Accurate Calorie Estimation**
  - Integrates with nutrition APIs like Nutritionix or Edamam
  - Provides real-time calorie content for recognized food items
  - Enables precise dietary tracking

- **End-to-End Solution**
  - Seamless workflow from image input to food classification and calorie estimation
  - User-friendly interface through Jupyter Notebook

## Dataset

### Food-101 Dataset
- **Source**: [Kaggle Food-101 Dataset](https://www.kaggle.com/datasets/dansbecker/food-101)
- **Composition**: 
  - 101 food categories
  - 1,000 images per category
  - Total of 101,000 images
- **Purpose**: Training and validating the image classification model

## Prerequisites

### System Requirements
- Python 3.7+
- pip package manager
- Jupyter Notebook
- (Optional) GPU for faster model training

### Dependencies
- TensorFlow
- Matplotlib
- NumPy
- OpenCV
- Collections

## Installation and Setup

### 1. Clone the Repository
```bash
git clone https://github.com/hk151109/PRODIGY_ML_05.git
cd PRODIGY_ML_05
```

### 2. Create Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies
```bash
pip install tensorflow matplotlib numpy collections opencv-python
```

### 4. Prepare the Dataset
- Download the Food-101 dataset from Kaggle
- Place the dataset in the specified project directory
- Follow the notebook's instructions for dataset preparation

## Running the Project

### Launch Jupyter Notebook
```bash
jupyter notebook
```

### Execute the Notebook
1. Open `food-item-recognition-and-calorie-estimation.ipynb`
2. Run cells sequentially:
   - Data loading and preprocessing
   - Model training
   - Model evaluation
   - Calorie prediction

**Tip**: Use **Shift + Enter** or click **Run** to execute cells

## Additional Configuration

### Performance Optimization
- **GPU Usage**: Recommended for large dataset training
- Adjust batch sizes and model parameters as needed

## Limitations and Considerations
- Model accuracy depends on training data quality
- Calorie estimates are approximations

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

**Happy Tracking and Healthy Eating!** 🥗📸🔍
