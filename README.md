# pradeep-pujari-share
This repository is for files shared with Udacity mentor, Pradeep Pujari.

Files shared:

2. Part 7 - Loading Image Data (Exercises) - v2.ipynb

Updated version of Jupyter notebook for Udacity's AI Programming with Python Nanodegree, Part 6. Neural Networks, Lesson 4: Deep Learning with PyTorch, Concept 20. Loading Image Data, Optional TODO: Attempt to build a network to classify cats vs dogs from this dataset. 

Associated repository: https://github.com/udacity/deep-learning-v2-pytorch.git

The bottom of this file contains a postscript that describes the problem in the execution of the training as reflected in the output from a full run of the notebook. It's worth noting that in my Notebook Workspace, the folder "Cat_Dog_data2" had an empty "test" folder and train/cat and train/dog folders which contained only the first 64 files from the corresponding "Cat_Dog_data" folders, as part of the attempt to sample an equal number of batches between cat and dog images.

1. Part 7 - Loading Image Data (Exercises).ipynb

Work-in-progress file for Udacity's AI Programming with Python Nanodegree, Part 6. Neural Networks, Lesson 4: Deep Learning with PyTorch, Concept 20. Loading Image Data, Optional TODO: Attempt to build a network to classify cats vs dogs from this dataset. 

Associated repository: https://github.com/udacity/deep-learning-v2-pytorch.git

My method using grayscale versions of the input image data executed without error on the training dataset training process, but produced an error in the validation dataset model forward pass. Pradeep correctly pointed out that I neglected to flatten my images for the validation steps. I corrected this error in the corresponding Udacity notebook workspace's Jupyter notebook.

