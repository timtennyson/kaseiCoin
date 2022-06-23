# kaseiCoin
A token for a hypothetical Mars colony

## Technologies

[Remix](https://remix.ethereum.org/)
[Ganache](https://trufflesuite.com/ganache/)
[Metamask](https://metamask.io/)


## Installation Guide

1) Install the metamask browser extension.
2) Install ganache
3) Using Ganache, import your wallet addresses into metamask. Set up the metamask network to connect to your local Ganache network.
4) Upload the Solidity (.sol) files into Remix.


## Usage

First, you'll compile and deploy the Solidity files in Remix. Using the crowdsale deployer contract, select a wallet address and mint the initial tokens and initialize the crowdsale. Connect metamask to the Remix website. Confirm the transaction in metamask. Then input the newly created crowdsale contract address and token contract addresses into the sidebar and you can now interact with it using your wallet addresses from ganache to purchase tokens. Select the amount of ETH you want to spend on the sidebar and then click transact. Approve the transaction. The balance of a given account can be viewed by calling the balance_of function or by adding the token using the token address into metamast so that it can be viewed there.

Examples Below:


!['DeployKaseiCoin'](https://github.com/timtennyson/kaseiCoin/blob/main/deploykaseicoin.jpg)
Deploy the KaseiCoin contract
!['DeployCrowdSale'](https://github.com/timtennyson/kaseiCoin/blob/main/deploycrowdsaleremix.jpg)
Deploy the Crowd Sale contract
!['ViewTxninGanache'](https://github.com/timtennyson/kaseiCoin/blob/main/ganacheconfirmation.jpg)
View transactions in Ganache
!['ViewTokenBalace'](https://github.com/timtennyson/kaseiCoin/blob/main/tokenbalance.jpg)
View token balance in Metamask
!['ViewPurchaseTxn'](https://github.com/timtennyson/kaseiCoin/blob/main/tokenspurchased.jpg)
View/get the transaction details using metamask


## Contributors
Tim Tennyson


## License
Open Source
