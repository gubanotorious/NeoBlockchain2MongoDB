# NeoBlockchain2MongoDB

## Introduction:

The program can transfer data from NeoBlockchain to MongoDB. This program can be used as a blockchain browser's warehousing program.

Support for the display of global assets registered through Smart Contracts will temporarily not support NEP-5 assets, and will be updated later to support NEP-5.

## Instructions:

1. Install MongoDB [Download link] (https://www.mongodb.com/download-center#community) [Operating Instructions] (https://docs.mongodb.com/manual/tutorial/install-mongodb-on- Windows/)

2. Install neo-cli and start the rpc service [Installation Instructions] (http://docs.neo.org/en/node/setup.html) [Command Reference] (http://docs.neo.org /zh-cn/node/cli.html)

3. Configure MongoDB link string and neo-cli rpc request address in App.config

4. Run the NeoBlockchain2MongoDB program

## screenshot:

Screenshot from MongoDB's own visual management tool MongoDB Compass Community

The screenshot ends at block height 1038735 (block number 1038736)

set

![Address](Sreenshot/neo.png)

Address
Record all addresses, transactions for each address, balance for each address (Coins)
![Address](Sreenshot/Address.png)

Asset
Record all assets, each asset's name, total amount, precision, owner, administrator, transaction list and other information
![Asset](Sreenshot/Asset.png)

Block
Record all block headers and transaction IDs
![Block](Sreenshot/Block.png)

Coin
Record all Coin, and each Coin asset ID, asset name, quantity, status, source and destination information
![Coin](Sreenshot/Coin.png)

MinerTransaction
Record all MinerTransactions and store MinerTransaction separately to speed up Transaction collection processing
![MinerTransaction](Sreenshot/MinerTransaction.png)

Transaction
Record all Transaction, details of each transaction, detailed transaction output, and transaction output
![Transaction](Sreenshot/Transaction.png)
