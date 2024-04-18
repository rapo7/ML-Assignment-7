# Setup 

## clone this repo 

```sh
git clone https://github.com/rapo7/ML-Assignment-7.git
```

## create a virtualenv 

```sh
python3 -m venv venv`
```
## Activate the venv 
```sh
source venv/bin/activate`
```
or for windows 
```cmd
venv\Scripts\activate
```

## Install all the requirements

```sh
pip install -r requirements.txt
```

## Downlaod the llama model
Downlaod the llama model from huggingface [LLama Model Downlaod](https://huggingface.co/TheBloke/Llama-2-7b-Chat-GGUF/resolve/main/llama-2-7b-chat.Q4_K_M.gguf)
## Create a folder named `model`

place the LLama model file in the `model` folder


## Run the project

```sh
streamlit run app.py
```
