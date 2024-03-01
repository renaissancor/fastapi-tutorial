
# Fast API Tutorial Setup Guide 

1. install python and create directory 

If you haven't already installed Python, you can do so using Homebrew 
Create a directory where you'll store your FastAPI project. 
You can name it whatever you like. For example:

```bash 
brew install python 
mkdir fastapi 
cd fastapi 
``` 

2. Create a Virtual Environment 

Create a virtual environment using Python's built-in venv module inside your project directory

```bash 
python -m venv env
```

3. Activate the Virtual Environment 

```bash
source env/bin/activate # Mac OS 
.\env\Scripts\activate # Windows 
``` 

4. Install Uvicorn and FastAPI 
```python 
pip3 install uvicorn fastapi 
``` 

5. Start the FastAPI tutorial 

6. Deactivate the Virtual Environment (Optional) 

When you're done working on your FastAPI project, you can deactivate the virtual environment using:
```bash
deactivate 
``` 

## Start and Finish Guide 

Activate Python Virtual Environment 


```bash 
source env/bin/activate # Mac OS 
.\env\Scripts\activate # Windows 
```

Run uvicorn 

```bash 
uvicorn main:app --reload 
``` 


Documentation Link based on OpenAPI Standard 

Open http://127.0.0.1:8000/docs 

FastAPI alternative API documation by ReDoc 

http://127.0.0.1:8000/redoc

Finish Python Virtual Environment 

```
deactivate 
```