# Report_AMLS_21-22-_SN20046378

## 1.Introduction

This project based on the Machine learning  algorithms to Classify Brain  MRI dataset, the images are in grayscale and are manually classified into 4 classes based on tumor type. There are two tasks: binary classification and multiclass classification.

binary classification: whether is a tumor

multiclass classification: no tumor, meningioma_tumor, glioma_tumor, pituitary_tumor

## 2.Organization of files

### Files:

**1.Data Pre-process.ipynb** is the first step to prepare and preprocess data

**2.Binary task-model.ipynb** is the second step to perform  and train model for binary task

**3.Multiclass task-model.ipynb** is the thrid step to perform  and train Support Vector Machine (SVM) model for multiclass task

**4.Multiclass task-model MLP.ipynb** is the fourth step to perform  and train Multi-layer Perceptron classifier (MLP) model for multiclass task

**5.Test.ipynb** is the final step to test trained models.



**Random Forest.ipynb** trains Random Forest model for binary task, but it is <u>not contained in paper</u>



**Data_reduced.npy** is the training images data after PCA:

​	It generated by: 1.Data Pre-process.ipynb 

​	and is loaded by: 2.Binary task-model.ipynb, 3.Multiclass task-model.ipynb, 4.Multiclass task-model MLP.ipynb  



**test_reduced.npy** is the testing images data after PCA:

​	It generated and is loaded by: 5.Test.ipynb

### Folder:

**dataset**: sample images with a .csv file containing labels.

**test**: testing images with a .csv file containing labels.

**Diagram**: folder for saving tables and diagrams generated in programs.

**model**: folder for saving models generated in programs.

- [x] notes： As pac model is large, it is not contained in model folder, while it can be generated by running <u>1.Data Pre-process.ipynb</u> 

## 3.Necessary packages or header files



| packages             | version |
| -------------------- | ------- |
| joblib               | 1.1.0   |
| matplotlib           | 3.5.0   |
| numpy                | 1.21.2  |
| opencv               | 3.4.2   |
| openpyxl             | 3.0.9   |
| pandas               | 1.3.4   |
| scikit-learn         | 1.0.1   |
| tensorflow-gpu       | 2.1.0   |
| tensorflow-estimator | 2.1.0   |

