![image](https://github.com/user-attachments/assets/816e3820-0861-4b59-92c8-4bd608239a4c)# Block-Chain Based Voting System

This project is blockchain based voting dapp created in React and Solidity.

## Project Description

“Blockchain Based Voting System” is a web based online voting system primarily based on ethereum blockchain technology. Blockchain is a transparent, distributed, immutable and trustless ledger and to overcome the problems of the traditional voting system, blockchain plays a vital role in terms of security, trust and more. Here anyone eligible for voting can vote for their favorite candidate and they can see the result after the end of the election. It is fast, secure, and has low cost as compared to traditional voting systems. Some key features of our system are:

a) Decentralized & Transparent

b) Trustless

c) Immutable

This project is a simple implementation of a voting system done to understand the basics of ethereum blockchain technology and the working mechanism of decentralized application made in Solidity and React. Here, one account who deploys the smart contract is the Admin and he/she can add voters and candidates that are eligible to cast the vote.  Then, the admin starts the election and eligible voters can vote for their favorite candidate. Finally, when admin ends the election, the voters can immediately see the final result of the election.

## Screenshots
//VOTERS DASHBOARD
![WhatsApp Image 2024-09-17 at 17 27 39_7e104cc2](https://github.com/user-attachments/assets/8f0c85f2-6201-4865-9e23-0af0c657b76c)
![WhatsApp Image 2024-09-17 at 17 27 55_f7b61e4c](https://github.com/user-attachments/assets/3fa1a711-e272-4f1c-b1ab-433f5cc3d4da)


//ADMIN DASHBOARD
![WhatsApp Image 2024-09-17 at 17 36 47_d7c300a7](https://github.com/user-attachments/assets/085957d8-a438-4316-a39d-79c4ad2c332b)


## Installation

### Step 1. Clone the project

```git clone https://github.com/yashc18/Blockchai-voting-app```

### Step 2. Start Ganache

Open the Ganache GUI client to start the local blockchain instance.

### Step 3. Compile & Deploy Election Smart Contract

```truffle migrate --reset```

We must migrate the election smart contract each time restart ganache.

### Step 4. Configure Metamask

- Unlock Metamask
- Connect metamask to the local Etherum blockchain provided by Ganache.
- Import an account provided by Ganache.

### Step 5. Run the Front End Application

```powershell
cd .\client
yarn install
yarn start
```

Visit URL in your browser: <http://localhost:3000>

## Next Steps

- Better legitimate user checking through biometrics
- Better voters and candidate data insertion
- Multiple candidate positions for voting
