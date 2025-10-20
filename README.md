# experiments_with_llms
My leanrnings and experiments with LLMs. 

## Using Langchain
* Building my own Deep Agent using LangChain with help from LangChain Academy and Dmitry Labazkin [1]. 
    * LangChain is a software framework that helps facilitate the integration of large language models into applications. 
    * As a language model integration framework, LangChain's use-cases largely overlap with those of language models in general, including document analysis and summarization, chatbots, and code analysis.
## Quick start
```bash
# clone
git clone https://github.com/sanjaysp91/experiments_with_llms.git
cd langchain

# setup environment 
langchain % python3 -m venv .venv    # create local python environment 
langchain % source .venv/bin/activate    # activate local python environment 
langchain % python3 --version    # ensure that python version is 3.13 or above 
Python 3.13.3    # output on my terminal 
```

## Install manually and create requirements.txt for future reference 
```bash
langchain % python3 -m pip install jupyterlab    # install jupyterlab python package 
langchain % pip freeze | grep 'jupyterlab==' >> requirements.txt    # manually add a specific package to the requirements file 
langchain % cat requirements.txt    # check the file contents 
```
## Install using requirements.txt
```bash
pip install -r requirements.txt    # install python packages from file 
```

## Usage

## Configuration
Important config files or env vars.
- CONFIG_FILE: ./config.yml
- ENV_VAR: EXAMPLE_KEY

## Contributing
Small note on how to contribute.
- Fork → branch → PR

## License
NA 

## Contact
Author — Sanjay Patel 

## References 
[1]: Project: Deep Agents with LangGraph: https://academy.langchain.com 