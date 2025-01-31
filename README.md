# Machine Learning Projects
This repository contains various Machine Learning projects developed for learning, participating in Kaggle competitions, and applying predictive modeling techniques. Each repository contains a Jupyter notebook explaining the project development.

## Projects
### 1. Bulldozer Price Prediction
**Description:** Machine Learning model to predict the selling price of bulldozers based on historical data.
- **Techniques used:** Regression, feature engineering, Random Forest, Gradient Boosting.
- **Data:** Available on [Kaggle - Blue Book for Bulldozers](https://www.kaggle.com/c/bluebook-for-bulldozers).
- **Objective:** Predict the price of a bulldozer at a given point in time based on its characteristics.

### 2. Dog Breed Prediction
**Description:** Dog breed classification model based on images.
- **Techniques used:** Convolutional Neural Networks (CNNs), Transfer Learning (ResNet, VGG, EfficientNet).
- **Data:** Available on [Dataset of dog images labeled by breed](https://www.kaggle.com/c/dog-breed-identification/overview).
- **Objective:** Correctly classify the breed of a dog from an image.

### 3. Heart Disease Prediction
**Description:** Machine Learning model to predict the presence of heart disease based on clinical data.
- **Techniques used:** Classification, Random Forest, Support Vector Machines, Logistic Regression.
- **Data:** Available on [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset/data).
- **Objective:** Predict whether a patient has heart disease based on medical variables.

### 4. Spaceship Titanic Prediction
**Description:** Predicting passenger survival in the Spaceship Titanic Kaggle competition.
- **Techniques used:** Classification, feature engineering, ensemble learning.
- **Data:** Available on [Kaggle - Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic).
- **Objective:** Determine if a passenger was transported to another dimension based on given features.

## Requirements
To run the projects locally, create a Conda environment and install the necessary dependencies:

```bash
cd project-directory
conda env create --prefix ./env --file environment.yml
```

## How to Run
Each project has a corresponding notebook. To execute:
```bash
conda activate ./env
jupyter notebook
```

## Contact
If you have any questions or suggestions, feel free to get in touch or contribute to the repository! This repository is under [LICENSE](LICENSE)
