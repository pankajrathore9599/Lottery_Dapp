# LotteryProject

## Description

You have to create a lottery smart contract.

**In this we will have two entities -**

1. Manager - It will deploy the smart contract.
2. Players - These will participate in the lottery.

In order to participate in the lottery the players must pay exactly 0.1 ether to the contract balance.

The lottery winner will be picked randomly by the manger only.And whosoever be the winner. The entire contract's ether balance will be transferred to the winner's account.

**Note -** There must be at-least three players for the manager to pick the winner of the lottery.

Some functions that you should have in your smart contract -

1. constructor() - To save the address of the manager.
2. getBalance() - To get the balance of the smart contract.
3. random() - To generate a random number.This will help you to randomly pick a winner.
4. pickWinner() - To pick the winner of the smart contract.

## Project checklist

- [ ] Functionality to save the address of the manager.
- [ ] Functionality to participate in the lottery.
- [ ] Functionality to pick the winner of the contract randomly.
- [ ] Functionality to get the balance of the contract.
