# VBanking Design

## Overall

![Overall design](web3-VBank%20Architecture.drawio.png)

## Blockchain Tech Stack

- Solidity
- Hardhat
- Ethersjs
- ERC20
- EIP-2612 (ERC20 Permit)
- ERC20 Permit2
- EIP-3009
- UUPS Proxy pattern
- Error Handling
- ERC2771 Forwarder (Relayer, Meta Tx)
- OwnableUpgradeable
- ReentrancyGuardUpgradeable
- Namespaced StorageLayout
- Storage Gap Pattern
- SafeERC20

## Token

- FLIP

## App Features

- SignUp
- Connect to Wallet
- Deposit from Wallet
- Withdraw to Wallet
- Exchange between (ETH/LINK, FLIP)
- Sign an allowance
- Schedule Payments
- Interest

## Contracts

BankApp

- accounts
- wallets (binding)
- exchange
- withdraw

BankToken (FLIP)

- issue
- transfer
- transferFrom
- permit
- balanceOf
- allowance

## Actions

- Time-based Scheudle
- Event-driven

## Rewards

- Bank reward to customer on Specific Events

## APIs

- onboarding
- wallet binding
- event tracking

## Implementations

<https://github.com/lucasdengcn/vbank-contracts>

<https://github.com/lucasdengcn/vbank-frontend>
