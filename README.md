# UtilityVehicles

## Code and data for the paper 'Visual examination of relations between known classes for neural network classifiers'

In this repository, we include data and components that can be used to reproduce the results obtained for the purpose of the paper 'Visual examination of relations between known classes for neural network classifiers'. 

Below, we describe all the components of the repository:
* UtilityVehicles - a folder with the UtilityVehicles dataset. It includes different instances of 10 vehicles (utility vehicles - used for different applications in production facilities and around them).
* mapping_dictionary.txt
* transfer_learning_mobilenetv2_save_category_data.ipynb - a jupyter-lab notebook that can be used to fine-tune a MobileNetV2 (https://keras.io/api/applications/mobilenet/#mobilenetv2-function) model on our UtilityVehicles dataset and to save the class representations to a csv file (these representations are used by the methods based on hierarchical clustering and MDS).
* mobilenetv2_weights_transfer_learning.csv  - sample csv file (used for the purpose of the results generation in our paper)
* hierarchical_clustering_final.ows - a pipeline in Orange that can be used to repproduce our results (as an alternative different implementations of Hierarchical Clustering and MDS can be used). 


Necessary packages for Python (+ Orange 3.34.0):
* pandas                       2.0.0
* tensorflow                   2.10.0
* numpy                        1.24.3


