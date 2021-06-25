# voting-smart-contract
A simple smart contract for voting. This contract is integrated using Remix IDE.

## Overview
This contract is oriented for ether holders.

Contract ```VotingPortal``` is using ```Wallet``` as an external contract. VotingPortal interacts with Wallet to earn credits for a user depending upon ethers stored in a wallet. 
These credits leverages a user an ability to vote in a poll.

There is a one-to-one relationship between ether and voting credit. 

Users can express how strongly they feel about an issue. That is using credits users can vote to show how much positive or negative they feel for an issue.
Voting point lies in the range of -credit to +credit.


