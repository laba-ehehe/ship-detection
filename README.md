# EEL4930 Project 2 - Dimensionality Reduction and Classification: Ship Detection Dataset

An analysis of a satellite imagery dataset for ship detection using dimensionality reduction and machine learning models.

## Table of Contents
- [About The Project](#about-the-project)
- [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Dependencies](#dependencies)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Authors](#authors)
- [Acknowledgements](#acknowledgements)

## About The Project

This project explores a satellite imagery dataset containing ship and no-ship images. The primary goals are to perform dimensionality reduction with Principal Component Analysis (PCA) and manifold learning (Isomap), then build and evaluate machine learning classifiers on the reduced datasets. The project compares the performance and efficiency of different models with and without dimensionality reduction.

### Built With
* Python 3.x
* scikit-learn
* pandas
* numpy
* matplotlib
* joblib

## Getting Started

### Dependencies

* pandas 1.5.0
* numpy 1.23.0
* scikit-learn 1.2.2
* matplotlib 3.6.1
* joblib 1.1.0

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/UF-MLforAISystems-Fall24/project-2-undergraduate-laba-ehehe.git
   ```
2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebooks:
   ```bash
   jupyter notebook "train.ipynb"
   jupyter notebook "test.ipynb"
   ```

Due to file size constraints, the trained models and dataset are hosted on Google Drive. Please download the required files from the link below:

[Download Models and Dataset](https://drive.google.com/drive/folders/1gGFTGyL6_cVj6MwEGkDo6QbplPux_hTC?usp=drive_link)

After downloading, ensuring all the files are in the root directory (`project-2-undergraduate-laba-ehehe`) and the dataset files (`ship_data.npy` and `ship_labels.npy`) are in the `ships_dataset` folder.

## Usage

The main tasks of this project include:
- Performing dimensionality reduction with PCA to retain 90% variance and visualizing the reconstructed images.
- Applying manifold learning (Isomap) to reduce dimensionality to two components and visualizing the dataset in the reduced space.
- Training and evaluating Random Forest and SVM classifiers on the original, PCA-reduced, and Isomap-reduced datasets.
- Comparing model performance in terms of accuracy, F1-score, training time, and inference time.

Key Jupyter notebooks:
1. `train.ipynb`: Data preprocessing, dimensionality reduction, and model training.
2. `test.ipynb`: Model evaluation and misclassification analysis.

## Contributing

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Authors

Lan Anh Do - [LinkedIn](https://www.linkedin.com/in/lananhnguyendo/)

Project Link: [GitHub](https://github.com/UF-MLforAISystems-Fall24/project-2-undergraduate-laba-ehehe.git)

## Acknowledgements

* [Dr. Catia Silva](https://faculty.eng.ufl.edu/catia-silva/) - Instructor of EEL4930 - Applied Machine Learning System (Fall 2024)
