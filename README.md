## Libraries used:

import numpy as np<br>
import pandas as pd<br>
import csv<br>
from sklearn.model_selection import train_test_split<br>
import matplotlib.pyplot as plt<br>
import seaborn as sns<br>
from datetime import datetime<br>
import os<br>
from scipy import sparse<br>
import time<br>
from sklearn.metrics.pairwise import cosine_similarity<br>
from surprise import Reader, Dataset<br>
import random<br>
import xgboost as xgb<br>
from surprise import SVDpp<br>
from surprise import SVD<br>
from surprise import KNNBaseline<br>
from surprise import SlopeOne<br>
from surprise import CoClustering<br>
from surprise import BaselineOnly<br>

## System Requirements:
-> Intel i7<br>
-> 16 GB RAM<br>
-> GTX 2060   RAM 6GB

## How to run the code

All the dataset files could be downloaded from Kaggle dataset. Once the dataset is downloaded, the code has to be reconfigured and mapped to the files stored in the directory.

## Time taken to run the project:

As the dataset is of size 2 GB, the whole execution of project may take greater than 20 hours to execute completely.
The exact time taken to train and test ML models are shown in te code respectively.
