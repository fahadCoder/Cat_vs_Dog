# Cat_vs_Dog

# Cat vs Dog Image Classification

A deep learning project for binary image classification using **TensorFlow, Keras, and transfer learning with Xception**. The model classifies images as cats or dogs using a pretrained ImageNet feature extractor.

## Model Overview

- **Architecture:** Xception (pretrained on ImageNet)
- **Input Size:** 256 × 256 pixels
- **Classification:** Binary (Cat / Dog)
- **Optimizer:** Adam
- **Loss Function:** Binary Cross-Entropy
- **Regularization:** Dropout and data augmentation

## Dataset

The project uses the [Dogs vs Cats dataset](https://www.kaggle.com/datasets/salader/dogs-vs-cats) from Kaggle.

- Training images: 20,000
- Validation images: 5,000

## Results

| Metric | Result |
|---|---|
| Training Accuracy | 99.42% |
| Validation Accuracy | **99.20%** |
| Training Epochs | 10 |

## Technologies Used

Python · TensorFlow · Keras · Xception · NumPy · Pandas · Matplotlib · Seaborn

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/fahadCoder/Cat_vs_Dog.git
   ```
2. Open `Cat_vs_Dog.ipynb` in Google Colab.
3. Upload your Kaggle API credentials (`kaggle.json`).
4. Run the notebook cells sequentially to download the dataset, train the model, and visualize the results.

## Project Highlights

- Transfer learning using pretrained Xception features
- Image augmentation to improve generalization
- Early stopping and learning-rate scheduling
- Training and validation performance visualization

## Author

[GitHub – fahadCoder](https://github.com/fahadCoder)
