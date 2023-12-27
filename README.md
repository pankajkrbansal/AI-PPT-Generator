# AI-PPT-Generator

##  About
This code repository shows 2 different approaches using the latest Chat GPT Function Calling & Assistant API to create your presentations

## Technology Used
- Python3
- ChatGPT
- pptx

## Project Setup
To start running the project follow the given instruction
- Create OPENAI Key from OPENAI platform.
- Using the given `env.example` file create `.env` file & place your key in it.
- Run command

 ```pip install -r requirements.txt```. 

This will install all the required packages for the project.

## Create PPT Using Function Calling
- If you want to create ppt using function calling, you need to use `fx-call-gpt3.py` file present in the root directory. At time of creqating this project, `user_prompt` is kept hardcoded, but you can change it as per your use case.
- To run this file you need to call it using python3.
```
python3 fx-call-gpt3.py
```
- After running your presentation will be stored in a folder named `powerpoint-ppt`

## Create PPT Using Assistant API
- If you want to create ppt using assistant API, you need to use `assistant-api-gpt4.py` file present in the root directory.
- To run this file you need to call it using python3.
```
python3 assistant-api-gpt4.py
```
- After running your presentation will be stored in a folder named `powerpoint-ppt`