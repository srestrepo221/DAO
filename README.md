# DAO

This project demonstrates a basic DAO use case. It comes with a ERC-20 contract that can be used to create tokens that will be distributed to investors. As well as a test for that contract, and a script that deploys that contract.
The voting for this DAO works based on Token Weighted Voting.
Anytime a proposal is created investors will vote on it and the quorum to reach is greater than 50%.
Basically over 50% of the votes must be casted in order for the proposal to pass.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
npm run deploy/localhost
npm run seed/localhost
npm run start
```
