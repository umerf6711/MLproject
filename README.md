## End to End Machine Learning project

Go to GitHub profile and create a new reposistory named it 'ML Project' . 

Create a folder in local drive named as 'ML Project' , copy its path and past it in anaconda prompt as 'cd D:\dataScience\ML Project'. Now move to this drive in anaconda prompt as D: and type 'code .' to open VS.

First of all create a new enviroment named as 'venv' by typing 'conda create -p venv python==3.10 -y'. -y is for permission to create venv. 

Activate created enviroment 'conda activate venv/'

Create file in VS to discribe the entire poroject discription set by sep by just click on new file named it as 'README.md' .

Create one more file by click on new file and named it '.gitignore' . 

Follow the step mentioned in created repository to connect with GitHub.

Create a file named as 'requirements.txt' to add on required python libraries to be used.

Create a file named as 'setup.py' .setup.py is a module used to build and distribute Python packages.

Create a source folder named 'scr'. In scr create a new file __init__.py . The __init__.py files are required to make Python treat directories containing the file as packages.

Push it to GitHub.

#components
components are modules that will use in project
Create a folder named 'components',create .py files in this folder with following names:
1.__init__.py
2.data_ingestion.py (to write code to fetch data from any wesite or ant=y external source, data devision into train and test data write in this code)
3.data_transformation (to write code to detail with different features of data )
4.model_trainer.py ( contains training code)

#pipeline
Create a folder named pipeline
1. train_pipeline.py (containg code for training pipeline and call the components)
2. predict_pipeline.py(contains code for prediction of model)
3. Create a file __init__.py

In src create three more file:
1. exception.py 
2. logger.py
3. utils.py 

## Code

#exception.py
An exception is an event, which occurs during the execution of a program that disrupts the normal flow of the program's instructions.

#logger.py

## Selection of a Machine Learning Project

I have slected 'Student Performance Indicator' project.
Dataset is available here in my github profile.

Create a folder named 'notebook'. Create a folder in notebook folder named 'data'. upload the data set 'stud.csv'.
Create two .ipynb files named EDA student performance and model training.

Now open the EDA student performance.ipynb file and start working.

Each and every step is mentioned in kernel.

## data_ingestion.py
All the code related to the data reading or data importing from any source. then creating a file 'artifacts' and save the data file here and code for devision of data into train and test data is done in this .py file.

## data_transformation.py
Code related to data taransformation like categorical to numerical data and creating pipline is done here.

## model_training.py
here we are going to train different models and checking r2_score and selecting the best model.
