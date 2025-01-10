I will use this as a pit stop. everytime I stop I will add the conclusion/ problems and solutions I found out

ask Tav
1. in tutorial 2 ie 3rd video in playlist he said that he is doing everything from scratch but later on we can automate it using template.py, ask how to do it

Steps performed Jan 10th
- Created bosvenv
- Connected to github
- Created Readme file and pushed to git
- Created .gitignore file on github set language python and pulled it in vscode
- created setup.py (search google setup.py to find out what it is)
- under main folder create src folder 
- under src, create "__init__.py" file this is used so that the folder gets considered as a package
- pushed files to github
- Started 2nd phase - Logging and Exception handling
- in src create folder "components" under components create "__init__.py", data_ingestion.py, data_transformation.py, model_training.py
- in src created another folder pipeline, under pipeline create train_pipeline.py, predict_pipeline.py, __init__.py
- under src create logger.py, exception.py, utils.py
- write custom exception code under exception.py
- write lgger code under logger.py

Problems with solutions 

prob- wasnt able to install bosvenv.
sol-updated conda and tried again it worked

Find out 

- if __name__=="__main__", what does this do