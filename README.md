# Fully-Convolutional-Network-PyTorch
For pixel-level binary classification (semantic segmentation):  
One object, two classes(background, object)  

# Environments
OS: Ubuntu 16.04 LTS  
Framework: PyTorch 1.2.0 with cuda  
Packages: NumPy, PIL, OpenCV-Python(3.4.2), etc...  
GPU: Nvidia Quadro-p4000 8gb  

# IMAGE SIZE
My image (and label) size: (3, 500, 500)  

# DATA FORM
Raw images should be in the directory of "/root/data/img"  
Label images should be in the directory of "/root/data/label"  
change root in fcn_dataset.py to your root path  

# TRAIN
1. python gen_data_txt.py  
2. python fcn_train.py

# INFERENCE
1. change "PATH_TO_PTH" in predict.py to your path_to_model_parameters  
2. change root to your dir_to_inference_images  
3. python predict.py  

# Reference
https://zhuanlan.zhihu.com/p/32506912
