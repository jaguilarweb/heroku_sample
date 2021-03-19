# Heroku Sample Project

## Introduction

This is a sample project to test this app on heroku.
This project belongs to the FSND program of UDACITY.


## Development Setup
1.	Download the project starter code locally
git clone https://github.com/udacity/FSND.git
cd FSND/projects/capstone/heroku_sample/starter

2.	Create an empty repository in your Github account online. To change the remote repository path in your local repository, use the commands below:
git remote -v 
git remote remove origin 
git remote add origin <https://github.com/<USERNAME>/<REPO_NAME>.git>
git branch -M master

3.	Initialize and activate a virtualenv using:
```
  python -m virtualenv env
  source env/bin/activate
 ```
Note - In Windows, the env does not have a bin directory. Therefore, you'd use the analogous command shown below:
source env/Scripts/activate

4.	Install the dependencies:
pip install -r requirements.txt

## Running the server

First, please ensure you are working using your created virtual environment.

To run the server, plese execute these commands:

```bash
source setup.sh
flask run
```

5.	Verify on the Browser
Navigate to project homepage http://127.0.0.1:5000/ or http://localhost:5000
