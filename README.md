In this project, we apply an implementation of U-Net to the Agriculture-Vision-2021 dataset, a massive image dataset containing aerial photos of crops. 
[You can read the paper here!](CV_Final_Project.pdf)

The notebook "testing-results.ipynb" contains everything you need to reproduce the results
from my report. Simply open the notebook in a directory containing the folders "ml_test_images",
"ml_test_labels", and the weights "v2_nir_water_checkpoint_1_epochs" (or just extract this ZIP to
one folder) and run all the cells! 


A few standard libraries which you likely already have are required, listed below:

PIL
os
torch
torchvision

If needed, all of these are installable with a simple `pip` install. I've left a cell at the top of the 
notebook which installs these libraries for you if needed!

The notebook "ag-vision.ipynb" contains all the code I used to train my model and preprocess the
(extremely unwieldy) dataset. You won't be able to run it without downloading the Agriculture-Vision dataset,
which is about 25 GB. Note that you absolutely DO NOT need to do this to reproduce my results!
