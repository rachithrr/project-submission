# project-submission
This repository is for submiting project codes of CSE574-Spring 2020. Please follow the submission instructions below to submit your project codes.

- Step 1: Search `CSE574Spring2020/project-submission`, then click 'Fork' on the topright corner.
- Step 2: New pull request (Base fork:Your/Base:master <— Head Fork: CSE574Spring2020's/Compare: master). Note that you may need to *1) switch the base for your comparison*, *2) compare across forks*, *3) creat pull request*, *4) merge pull request*, *5) confirm merge*. This step is important which merges this repository to your own's.
- Step 3: Upload your codes to your own repository.
- Step 4: Pull request (Base fork: CSE574Spring2020's/Base: **Your own brunch** <— Head Fork: Your own/Compare: Master).


##########
Running the code

->datacollection contains script to fetch data. This takes hours and has already been run and all the data is present in db. 
-> use news.db with data collected from previous step and run IML_shreyas.ipynb to add sentiment table. 
-> run lstm_combined_rachithr.ipynb with the news.db and out_df.tsv to obtain predictions. 
