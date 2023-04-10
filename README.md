# Fintech_Module19

![blockchain_crypto](https://github.com/nielsdehaan1977/Fintech_Module19/blob/main/Images/crypto.jpg)
---
# Simple streamlit app that lets it's users find fintech professionals from among a list of candidates, hire them, and pay them. 

---
## This python code can be utilized as an app by running Streamlit. The app provides a user friendly web interface. The app "Fintech Finder" is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. The Ethereum blockchain network is integrated into the application in order to enable customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

---
## fintech_finder.py
---
* The tool goes through the following steps:

* Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache
* Fetch and display the account balance associated with your Ethereum account address.
* Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.
* Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.
* Review the transaction hash code associated with the validated blockchain transaction.


---
## Table of Content

- [Tech](#technologies)
- [Installation Guide](#installation-guide)
- [Usage](#usage)
- [Contributor(s)](#contributor(s))
- [License(s)](#license(s))

---
## Tech

This project leverages python 3.9 with the following packages:
```
`Python 3.9`
```
* [streamlit](https://streamlit.io/) - Streamlit is an open-source Python library that makes it easy to create and share, custom web apps for machine learning and data science.

* [dataclasses](https://docs.python.org/3/library/dataclasses.html) - his module provides a decorator and functions for automatically adding generated special methods such as __init__() and __repr__() to user-defined classes.

* [typing](https://docs.python.org/3/library/typing.html) - This module provides runtime support for type hints.

* [web3](https://web3py.readthedocs.io/en/stable/) - web3.py is a Python library for interacting with Ethereum.

* [requests](https://requests.readthedocs.io/en/latest/) - Requests allows you to send HTTP/1.1 requests extremely easily

* [dotenv](https://pypi.org/project/python-dotenv/) - Python-dotenv reads key-value pairs from a .env file and can set them as environment variables.

* [bip44](https://pypi.org/project/bip44/) - Simple Python bip44 implementation. Mnemonic + bip32.

---

## Installation Guide

### Before running the application first install the following dependencies in either Gitbash or Terminal. (If not already installed)

#### Step1: Activate dev environment in Gitbash or Terminal to do so type:
```python
    conda activate dev
```
#### Step2: install the following libraries (if not installed yet) by typing:
```python
    pip install streamlit
    pip install web3==5.17
    pip install mnemonic
    pip install bip44
    

 ```
#### Step3: Start python file with RUN Streamlit
Streamlit can be started by:
1. Activate your developer environment in Terminal or Git Bash (already done in step 1)
2. Form the location where you cloned the github repository folder, type: ***Streamlit run fintech_finder.py***

![streamlit](https://github.com/nielsdehaan1977/Fintech_Module19/blob/main/Images/streamlit_start.jpg)


#### Step4: install ganache
please follow the instructions on the Ganache download page [ganache](https://trufflesuite.com/ganache/) to download and install this tool on your local machine. When you open Ganache, you are presented with two options for creating a workspace: Quickstart Ethereum and New Workspace Ethereum. Click Quickstart Ethereum.

![ganache](https://github.com/nielsdehaan1977/Fintech_Module19/blob/main/Images/ganache.png)


## Usage

To use the fintech_finder app, simply clone the full repository and open the **fintech_finder.py** file in via streamlit from your gitbash or terminal by using Step3 in above installation guide. 

The tool will go through the following steps:

* Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache

![account_instance](https://github.com/nielsdehaan1977/Fintech_Module19/blob/main/Images/env_ganache_aligned.jpg)


* Fetch and display the account balance associated with your Ethereum account address.

![account_balance](https://github.com/nielsdehaan1977/Fintech_Module19/blob/main/Images/streamlit3.jpg)

* Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

![account_value](https://github.com/nielsdehaan1977/Fintech_Module19/blob/main/Images/streamlit2.jpg)


* Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

![ganache_transaction](https://github.com/nielsdehaan1977/Fintech_Module19/blob/main/Images/streamlit5.jpg)

![ganache_transaction2](https://github.com/nielsdehaan1977/Fintech_Module19/blob/main/Images/streamlit6.jpg)

![ganache_transaction3](https://github.com/nielsdehaan1977/Fintech_Module19/blob/main/Images/streamlit7.jpg)

![ganache_transaction4](https://github.com/nielsdehaan1977/Fintech_Module19/blob/main/Images/streamlit8.jpg)


## Contributor(s)

This project was created by Niels de Haan (nlsdhn@gmail.com)

---

## License(s)

MIT