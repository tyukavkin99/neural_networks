requirements:
pandas==2.0.0
numpy==1.24.2
matplotlib==3.7.1
seaborn==0.12.2
torch==2.0.0
scikit-learn==1.2.2
torchmetrics==0.11.4

The required structure:
- Siergiej_Tiukawkin_individual_coursework.ipynb
- test_models.ipynb
- mlp_model.pt
- svm_pkl
- data
- - heart_2.csv
- - Xtest.csv
- - ytest.csv

setup_instructions:
1. Create a new environment
2. pip install -r requirements.txt
3. open test_models.ipynb
4. the datasets Xtest.csv and ytest.csv have to be in data folder
5. run the cells in "loading the data"
6. run the cells in "changing the data"
7. run the cells in "testing the MLP model"
8. run the cells in "testing the SVM model"
9. the outputs should be two confusion matrices