# Machine Learning — BYU CS 270

Four machine learning labs completed for BYU's CS 270 (Machine Learning), implemented in Jupyter notebooks using scikit-learn. Each lab applies a different fundamental machine learning algorithm to one or more real datasets, covering data preprocessing, model training, model evaluation, and analysis of results.

## Labs

| Lab | Folder | Description |
| --- | --- | --- |
| Clustering | [`clustering/`](clustering/) | K-means and agglomerative clustering, evaluated with silhouette scores. |
| Decision Trees | [`decision_trees/`](decision_trees/) | Decision tree classification and regression, including cross-validation and comparison against scikit-learn's built-in implementations. |
| K-Nearest Neighbors | [`knn/`](knn/) | KNN classification and regression with feature scaling. |
| Neural Networks | [`neural_networks/`](neural_networks/) | Backpropagation-based neural network classification and regression using scikit-learn's MLP models, with hyperparameter tuning via grid and randomized search, applied to Iris, vowel recognition, air quality, and red wine quality datasets. |

Each folder contains the notebook for that lab along with the datasets it uses.

## Setup

Clone the repo and install dependencies:

```sh
git clone https://github.com/samanthaljohn/machine-learning.git
cd machine-learning
pip install -r requirements.txt
```

Then launch Jupyter and open any notebook:

```sh
jupyter notebook
```

## Datasets

Most datasets are sourced from the UCI Machine Learning Repository, provided as `.arff` or `.csv` files alongside the relevant notebook. No external downloads are required — everything needed to run a notebook is included in its lab folder.