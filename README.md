# Mini_Project_23-24

Multi Disease Prediction Model

Welcome to the Multi Disease Prediction Model project! This project aims to provide a web application for predicting diseases such as Diabetes, Heart Disease, and Parkinson's using Machine Learning. The predictive models have been trained on relevant datasets, and the application is built using Python with Streamlit for a user-friendly interface.

To run the project on your system, you can follow the following steps:
1. Open three different Google Colaboratory notebooks and insert the datasets (one in each).
   Link to the datasets are in the repository (.csv files).
2. The Google Colab code files can be found in the above repository (.ipnyb files).
   Paste the code of each file corresponding to the datasets.
3. Once you run the models after uploading the dataset and code files. You will get the model files by Google Colab.
   The Model are also uploaded above (.sav files). Save these in your system.
Note- Keep saving all these files in a folder so we can access them easily.

I have used anoconda navigator for my project. Here are the steps for how to proceed in the anoconda navigator.
1. Install Spyder from the home section.
2. Create a new environment from the environment section. (Optional)
3. Open the spyder IDE and paste the code from "Multiple Disease Prediction.py". But we need to make some changes in the code.
   i. "# loading the saved models" below this heading I have copied three paths from my system. You need the copy the paths of the models we have saved in above step 3 and paste them here.
   ii. Then you need to replace all the "\" (backward slases) with "/" (forward slashes).
   iii. Add ,'rb' after pasting the code as shown in the file.
Note- Save the spyder file with the .py extension.

Open the new environment you have created and click on the "Open the terminal" option and download the following frameworks: 
1. Pickle (pip install pickle5)
2. Streamlit (pip install sreamlit)
3. Streamlit option menu (pip install streamlit-option-menu)
Note- The command may vary depending on the version of your system and exisiting frameworks. Search the browser in case of error.
   
To host the spyder file code we open the terminal and paste the following code with changes in your terminal.

streamlit run "C:\Users\gupta\OneDrive\Desktop\Mini Project\Multiple Disease Prediction.py" 
   Copy the path of your spyder file and then paste this command in your terminal.
   The local host will run in your browser.

