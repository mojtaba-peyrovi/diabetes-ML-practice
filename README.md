# Diabetes Challenge

After we learned some interesting algorithms to solve classification problems, it's time to implement them on new data and to compare their performance. You can find the challenge for today in the second notebook [Diabetes Challenge](2_Diabetes_Challenge.ipynb). If you need more information about the data set, you can have a look at the [Paper](Paper_on_Diabetes_Mellitus_Data_Set.pdf) included in this repo.

The first notebook will introduce the concept of **pipelines**. Sklearn provides us is with a module that makes the usage of pipelines fun and easy. 



## Environment

Use the requirements file in this repo to create a new virtual environment for this task.


```BASH
pyenv local 3.11.3 
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
If you are working on Windows type the following commands in the PowerShell:

```sh
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```