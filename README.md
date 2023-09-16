# Hyperparameter Tuning
Using scikit-learn `GridSearchCV` and `Pipeline` for ML hyperparameter tuning.

**Run the GridSearch Demo in a colab notebook**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/murilogustineli/hype-tuning/blob/main/gridsearch.ipynb)

⚠ _Colab provides a temporary environment: anything you do will be deleted after a while, so make sure you download any data you care about._

## Scikit-learn documentation:
* [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)
* [Pipeline](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html)
* [Breast Cancer dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)

### Presentation slides
* [Google Slides](https://docs.google.com/presentation/d/1sk1zOEicr-apXsn_42C2Jg7-yDZ0at5wzO5S2KaoMp4/edit?usp=sharing)

## Project Setup Guide

To ensure our project runs seamlessly, we'll set up a dedicated Python environment and install the necessary packages.
### Prerequisites

- Python (we're using Python 3 for this project)
- pip (Python package installer)
- Either `virtualenv` or `conda` (based on your preference)

### Setup Instructions
#### 1. Setting up a virtual environment

##### Using Conda:
First, [install Anaconda or Miniconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) based on your operating system.

Then, create a new environment:

```
conda create --name myenv python=3.8
```

Activate the environment:

```
conda activate myenv
```

##### Using virtualenv:
You can skip this step if you already have conda installed and did the previous step.
###### Windows:
```
pip install virtualenv
virtualenv myenv
.\myenv\Scripts\activate
```

###### Mac & Linux:
```
pip3 install virtualenv
virtualenv myenv
source myenv/bin/activate
```

#### 2. Installing the required packages

We have a `requirements.txt` file that lists all the necessary packages for this project.

Install the packages using:

```
pip install -r requirements.txt
```

If you're using Conda, while most of the packages are available directly through pip, some might have better support or performance when installed through Conda channels:

```
conda install --file requirements.txt
```

Creating the `requirements.txt` file:


### That's it!

Your environment is now set up with all the necessary packages. You can proceed with running or developing the project.
