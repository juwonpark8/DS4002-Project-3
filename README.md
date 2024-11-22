# DS4002-Project-3
# Section 1: Software and Platforms
Our code was written in Python using UVA OpenOnDemand (UVA HPC) in order to run the code faster than if we were to use Google Colab. For add-on packages, sklearn was used to split the data into training and testing sets. Tensorflow was used to run our two models: ResNet50V2 and VGG19. Matplotlib was used to evaluate the models and create visualizations.
# Section 2: Map of Documentation
In our repository, there are folders for the data, scripts, and output. The data is from a github repository on brain MRI image classification and is located in the Data folder.
- In the Data folder:
  - Data Appendix Project 3 .pdf: Data Appendix that includes tables, figures, and other descriptive statistics about the data
  - brain_tumor_dataset.zip: A folder containing subfolders of MRI images. "no" contains MRI scan images with no brain tumors and "yes" contains MRI scan images with brain tumors. 
- In the Scripts folder:
  - models.ipynb: Code used to run preprocessing, models, and validation
- In the Output folder:
  - Accuracy_and_Loss_Graphs.png: Graphs of accuracy and loss of ResNet50V2 and VGG19 models
# Section 3: Instructions for Reproducing Our Results
1. Navigate to the Data folder of our repository, and download the brain_tumor_dataset.zip folder. This is the MRI images dataset.
2. Navigate to the Scripts folder, where you will see a Python notebook script.
3. Download or copy the code from the models.ipynb file. This is the file needed to run the ResNet50V2 model and the VGG19 model.
5. Next, go to UVA OpenOnDemand (https://www.rc.virginia.edu/userinfo/hpc/ood/). On the top right of the menu bar of the Open OnDemand dashboard, click on Interactive Apps. In the drop-down box, click on JupyterLab.
6. Launch JupyterLab and keep all of the defaults listed. Open notebook and paste or upload code from the models.ipynb file.
7. Once notebook is running and code is pasted, make sure that the filepaths for the dataset are where you have the code stored on your local machine. Run the code by selecting Run -> Run All in the Juptyer Notebook tool bar. This will install all necessary packages, run the models, and evaluate the results.
# References
