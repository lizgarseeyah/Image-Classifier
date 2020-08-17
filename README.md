# Image Classifier

### Files:
- Image Classifer Project.ipynb: main file
- train.py: trains a new network on a dataset and saves the model as a checkpoint.
- predict.py: uses a trained network to predict the class for an input image.
- cat_to_name.json: mapping of categories to real names.
- workspace_utils.py: a module that includes an iterator wrapper called "keep_awake" and a context
                      manager called "active_session" that can be used to maintain an active session during
                      long running processes.

This projects builds an image classifier using PyTorch. The trained image classifier is used to identify a set of images.
