# How to read smart contracts

## Contents
### Introduction
### Application and benefits
### Analyzing and Reading contracts

-------------------------
## Introduction
A "smart contract" is simply a program that runs on the Ethereum blockchain. It's a collection of code (its functions) and data (its state) that resides at a specific address on the Ethereum blockchain. They typically are used to automate the execution of an agreement so that all participants can be immediately certain of the outcome, without any intermediary’s involvement or time loss. They can also automate a workflow, triggering the next action when conditions are met.

------------

## Application and benefits
1. Making transactions faster:  Once a condition mentioned in smart contract is met, the contracts associated are executed immediately. No time spent on manual processes like documentations and paperwork.
2. No need of third party: All the data of transaction is stored on a shared ledger in encrypted format. This also removes the possibility of altering information for personal benefit.
3. Secured Transactions: Blockchain transaction records are encrypted, which makes them very hard to hack. Moreover, because each record is connected to the previous and subsequent records on a distributed ledger, hackers would have to alter the entire chain to change a single record, which is nearly impossible.

--------------

## How to read smart contracts

However complex it may sound, it is afterall simply a digital contract. Like any other contract, it can be understood by reading terms and conditions (in this case, conditions in form of code).

[Etherscan](https://etherscan.io/) is a Block Explorer and Analytics Platform for Ethereum, a decentralized smart contracts platform. You can read everything about a transactions just by searching contract address or TXN hash.

So, by simply reading a smart contract you will be able to understand the popularity of a project, the ownership rights, details of all transactions, and much more.

For the starters, we will take a NFT contract of recently launched project ‘[Crypto Coven](https://opensea.io/collection/cryptocoven)’. Let’s get into it.

- Get on [Opensea.io](http://Opensea.io)  and open up our project. Click on any NFT and get the contract address from the details section.

![Opensea images](/assets/opensea.png)

- Search for the contract address on Etherscan. First and foremost, you will see general information related to NFT such a balance, name tag and creator. Let’s dive into them:

       1. Balance: Number of coins/tokens held by the contract

       2. Name Tag: These are private notes which can only viewed by YOU.

       3. Creator: Wallet address of the person who created and deployed the contract and a link to transaction (TXN hash). 

![Etherscan](/assets/etherscan.png)
 

- **Tracker**: It is the token tracker which tells us all the data about token like maximum supply, total transaction done, minimum price of token, number of holders and highest holding user.
- **Transactions**: Now, if you click on transactions tab, you can find all the NFT smart contract transactions listed chronologically along with the timestamps.
- **Method** is the function executed based on the input data. Usually, the methods are mint, set approval for all, and transfer from. Along with these, you can also see details such as transaction status, block in which the transaction was included in, transaction fee, wallet addresses that made the transaction as well as the one that received it, and much more. Pretty powerful, isn’t it?
- **Internal Txns**: Internal transactions is basically transaction between two contracts. Smart contracts are automated and are set to trigger once the conditions are met. Internal transactions are basically the value transfers that happen as a result of the smart contract execution. In layman terms, often, for a smart contract to execute, it requires a certain amount of ETH (or another token) transactions.

![Contract](/assets/contract.png)

- **Contract**: The Contract tab gives you all the information about the specific NFT smart contract. Under ‘Code’, you can see the contract’s source code. ‘Read Contract’ is for the general contract information and all its functions. Meanwhile, ‘Write Contract’ allows you to interact with the contract.
- **Analytics**: This section contains the analytic graphs showcasing transactions, fees, transfer of tokens, holding accounts and so on. It’s useful to understand the basic trend a particular project has in market.


## Though we won’t use these features everyday, it’s very important to understand and analyze smart contracts before we can conduct transactions on them.