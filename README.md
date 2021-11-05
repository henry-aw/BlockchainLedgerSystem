# *Module 18 Challenge*
## Blockchain-Based Ledger System with User-Friendly Interface

**Welcome to my Module 18 Challenge repository. Here, you can checkout the blockchain-based ledger system I created, complete with a user-friendly web interface, which allows for the transfer of money between senders and receivers and verifies the integrity of the data in the ledger. Find out more in the following sections!**

---

## Background
For this project, I acted as a fintech engineer who's working at one of the five largest bank's in the world. I was recently promoted to act as the lead developer on their decentralized finance team. My task was to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

Throughout the module, I created the basic PyChain ledger structure that this project implements. For this project, I made the following updates:
- Create a new data class named Record. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store.
- Change the existing Block data class by replacing the generic data attribute with a record attribute that's of the type Record.
- Create additional user input areas in the Streamlit applicaiton. These input areas should collect the relevant information for each financial record that you'll store in the PyChain ledger.
- Testing the PyChain ledger.

---

## Streamlit Application
The deployed streamlit application looks like this:
![Screen Shot 2021-11-05 at 3 37 41 PM](https://user-images.githubusercontent.com/86025349/140574515-32716d22-fadb-43ae-b359-6012ea173283.png)

I provided some sample input to demonstrate how the application functions.

---

## Technologies and Usage
This project leverages Python 3.7, Streamlit and the dataclasses, hashlib, and Pandas libraries with the following requirements and dependencies:
- import streamlit as st
- from dataclasses import dataclass
- from typing import Any, List
- import datetime as datetime
- import pandas as pd
- import hashlib
