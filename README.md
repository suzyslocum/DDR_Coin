# DDR_Coin
![ddr](./Images/dd_roulette.png)

---

## Designated Driver (DD) Roulette

---

### Background
We created a blockchain token system used to determine who will be designated driver among a group of friends when they go out

---

### Motivation 
To have a system in place for everyone to get home safely without one person always getting stuck being the DD, or the person who is supposed to be DD backing out and stranding everyone

---

### Questions to answer
* What is the consequence for not fulfilling your obligation if you are chosen as the DD
* Who will be included in your group
* What will be the incentive to participate
* Is this an ongoing system or one contract per event
---

### Instructions
To install the Web3.py library, check that your dev environment is active, and then run the following:
pip install web3==5.17

---
Create contract DDRCoin. Deploy contract. 
Name: DDRCoin
Symbol: DDR
Inital_supply: 40

// owner address: 0xD81b7D4224c017FC839Dc2a95D77Fbb6237B8383
// Created contract address: 0xF6F9BbAB7d8bbb668bD5cF3Ce3650dbec01338CE

// Create wallet for 4 individuals. Transfer 10 coins to each wallet

* Account1: Susannah = 0xD81b7D4224c017FC839Dc2a95D77Fbb6237B8383
* Account2: Sarah = 0xED8706cf7294f1c4F76D54EBEbD3b48D78C72CA6
* Account3: Callie = 0x9D3aD9827e8901AB4499BCbDBC3c48615780dbDF
* Account4: Gabriel = 0xEC9e323F61BCC0B23D40f779C1aC0AE43AE20264

// Add functions to store address and transfer funds to contract wallet / address

// Roulette assigns Designated Driver
// Transfer all 40 coins to the Designated Driver

// Create function to only payout after event date

## Technologies

The application is written in Solidity version 0.5.0, it was deployed and tested using the Ethereum Remix IDE, MetaMask, and Ganache.

Solidity - to create the smart contract [Solidity documentation](https://docs.soliditylang.org/en/v0.8.4/)

MetaMask - a software cryptocurrency wallet [MetaMask documentation](https://metamask.zendesk.com/hc/en-us)

Ganache - a personal blockchain for application development [Ganache documentation](https://www.trufflesuite.com/docs/ganache/overview)

Streamlit - to create the web application [Streamlit documentation](https://docs.streamlit.io/en/stable/)

os - miscellaneous operating system interfaces [os documentation](https://docs.python.org/3/library/os.html)

Requests - HTTP library for python [Pandas documentation](https://docs.python-requests.org/en/master/)

Dotenv - to read and add a key-value pair to an environment [Dotenv documentation](https://pypi.org/project/python-dotenv/)

Dataclass - provides a decorator and fucntions for automatically adding special methods to user-defined classes [Dataclass documentation](https://docs.python.org/3/library/dataclasses.html)

BIP44 - Bitcoin improvement proposals - [BIP44 documentation](https://www.cs.utexas.edu/users/moore/acl2/manuals/current/manual/index-seo.php/BITCOIN____BIP44?path=3370/27092/5157/6093/9771)

Web3 - an Ethereum Javascript API - [web3 documentation](https://web3js.readthedocs.io/en/v1.3.4/)

---

### Developers
* Callie Yu
* Gabriel Silva
* Sarah Kang
* Susannah Slocum
