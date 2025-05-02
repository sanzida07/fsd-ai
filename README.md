## Project Name: Futuristic Self-Driving Car: Leveraging CNNs, Deep Learning with TensorFlow

### Software:

1. PyCharm (Python IDE) or VS Code
2. A self-driving car simulator built with Unity
3. Git Bash
4. Anaconda

### Python Packages:

1. opencv-py
2. numpy
3. pandas
4. matplotlib
5. sklearn
6. imgaug
7. tensorflow

### Activate the Virtual Environment:

python -m venv env
.\env\bin\activate

### Install Packages

pip --version
pip install opencv-python numpy pandas matplotlib scikit-learn imgaug tensorflow

### Anaconda Setup

conda init bash
conda create --name cnnEnv
conda env list
conda activate cnnEnv
conda install python=3.10.13
conda list
which python
conda deactivate cnnEnv

### Anaconda Package

conda install tensorflow

### Verify Package Installed

import cv2
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import sklearn
import imgaug
import tensorflow as tf

print("All packages imported successfully.")
