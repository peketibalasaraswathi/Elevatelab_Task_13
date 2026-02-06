# Elevatelab_Task_13
## Dimensionality Reduction

##  Internship Task Overview
This project demonstrates **Principal Component Analysis (PCA) for dimensionality reduction using the Sklearn Digits dataset.  
The goal is to understand how feature compression affects model performance while preserving maximum variance.


## Tools & Technologies Used
- Python  
- Scikit-learn  
- NumPy  
- Matplotlib  
- Google Colab  


## Dataset
- Primary Dataset: MNIST (recommended)
-  Used Dataset:  Sklearn Digits Dataset  
  - 1797 samples  
  - 64 features (8×8 images flattened)  
  - 10 target classes (digits 0–9)


## Steps Performed
1. Loaded and explored the Digits dataset  
2. Flattened image data into feature vectors  
3. Applied  StandardScaler for feature normalization  
4. Implemented PCA with components: 2, 10, 30, 50 
5. Plotted **cumulative explained variance**  
6. Reduced dataset dimensions using PCA  
7. Trained **Logistic Regression*  on:
   - Original dataset  
   - PCA-reduced dataset  
8. Compared accuracy before and after PCA  
9. Visualized **2D PCA scatter plot**  


##  Results
- PCA significantly reduces feature dimensions  
- Accuracy remains competitive even with fewer components  
- 2D PCA visualization shows clear digit separation  


##  Visualizations Included
- Explained variance vs number of components  
- Cumulative variance plot  
- 2D PCA scatter plot  

## Output
<img width="1216" height="666" alt="Image" src="https://github.com/user-attachments/assets/41977154-03f8-4ac6-82b6-2a9af8a3c7ab" />
<img width="898" height="660" alt="Image" src="https://github.com/user-attachments/assets/53eafcf5-5b27-4991-aa64-6afd4c12fb6f" />
<img width="1309" height="393" alt="Image" src="https://github.com/user-attachments/assets/3125fc13-9c44-4cef-9302-fe8537df2170" />
