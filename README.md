# AptosX Token Mint Module

## Overview
The AptosX Token Mint Module is a smart contract for managing the minting, staking, and validator operations of a custom token, **AptosX Coin (APTX)**, on the Aptos blockchain. It provides a seamless way to stake AptosCoin, mint APTX, and manage validators.

## Key Functions

1. **initialize**
   - **Purpose:** Sets up the AptosX Coin (APTX) with mint, burn, and freeze capabilities, and initializes a stake vault for holding staked AptosCoin.

2. **deposit**
   - **Purpose:** Allows users to stake AptosCoin and receive an equivalent amount of AptosX Coin.

3. **withdraw**
   - **Purpose:** Enables users to withdraw their staked AptosCoin by burning the corresponding amount of AptosX Coin.

4. **add_validator / remove_validator**
   - **Purpose:** Manages a set of validators, ensuring only authorized accounts can modify the validator set.

## Usage
- **Initialize** the module with `initialize`.
- **Stake** AptosCoin using `deposit` and receive APTX.
- **Withdraw** your stake with `withdraw`.
- Manage validators with `add_validator` and `remove_validator`.

This module ensures secure and efficient token management, making it ideal for decentralized finance applications.
