# Detection-of-Receipt-s-TTC-amount-
@author: Nguyen Hoai nam

## Data

The data (images + json descriptions) can be found on this GitHub repository (https://github.com/clovaai/cord).

link to the corresponding paper: https://openreview.net/pdf?id=SJl3z659UH

Another way around is to copy data from this [link](https://drive.google.com/drive/folders/1_r2rgPKBqqFmEFoNvz2lQGfIIfRALJ_W) to the personal Drive.

## Using the code

The executable code can be ran from the main.ipynb notebook.

## Python requirements

Python 3.x with Torch 1.5.1+cu101 (GPU version) and all "classic" packages: numpy, matplotlib etc.

## The main points in this notebook are**

1. Extracting desired features from JSON files to detect total amount TTC.
2. The model used is a LayoutLMv3
3. For simplicity, only training on train data and validating on the test set are implemented