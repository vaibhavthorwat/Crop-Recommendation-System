# Crop-Recommendation-System

#Description: 
A crop recommendation system uses data analysis and machine learning to suggest the most suitable crops for a given plot of land. By analyzing factors such as soil type, weather conditions, and historical crop yield data, the system helps farmers optimize crop selection, improving yield and sustainability.

#Project Structure:
1:crop_classification_with_recommendation.ipynb: Jupyter notebook for training the crop classification and recommendation model.
2:main.py: Script to load the trained model and make crop recommendations.
3:model.pkl: Trained crop recommendation model (to be generated).
4:minmaxscaler.pkl: Serialized MinMaxScaler for data normalization.
5:standscaler.pkl: Serialized StandardScaler for data standardization.
6:requirements.txt: File containing the necessary Python libraries.

#Setup Instructions:
1:Clone the Repository  ==>  git clone 
2:Install Required Libraries ==>  pip install -r requirements.txt
3:Train the Models:Open the crop_classification_with_recommendation.ipynb notebook in Jupyter Notebook. Execute all cells to train the crop classification and recommendation models. This will generate model.pkl, minmaxscaler.pkl, and standscaler.pkl files.
4:Move Generated Files:Delete any existing model.pkl, minmaxscaler.pkl, and standscaler.pkl files in the project folder. Move the newly generated files from your local machine to the project folder.
5:Run the Main Script  ==> python main.py

#Files Description:
1:crop_classification_with_recommendation.ipynb: Notebook containing data preprocessing, model training, and evaluation.
2:model.pkl: Serialized model for crop recommendation.
3:minmaxscaler.pkl: Serialized MinMaxScaler for data normalization.
4:standscaler.pkl: Serialized StandardScaler for data standardization.
5:requirements.txt: List of required libraries for the project.
6:main.py: Script to load models and make crop recommendations.

#Notes:
1:Ensure that model.pkl, minmaxscaler.pkl, and standscaler.pkl files are in the same directory as main.py.
2:Update the requirements.txt file if additional libraries are required.

#Technologies Used:
1:Python: Programming language used for developing the project.
2:Pandas: Library for data manipulation and analysis. 
3:NumPy: Library for numerical computations.
4:Scikit-learn: Machine learning library used for building and evaluating models.
5:Jupyter Notebook: Interactive environment for running the Fertilizer Prediction.ipynb notebook.

#Credits:
This project was developed by Vaihav Thorwat and Rushikesh Lokhande as a part of Crop Recommendation System.


