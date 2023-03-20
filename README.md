# Decentralized voting application on Ethereum Blockchain


To run the code, you need to run the following commands. 

```shell
npm install
```

You first need to compile the contract and upload it to the blockchain network. Run the following commands to compile and upload the contract.


```shell
npx hardhat compile
npx hardhat run --network volta scripts/deploy.js
```

Once the contract is uploaded to the blockchain, copy the contract address and copy it in the .env file. 
You can also use another blockchain by writing the blockchain's endpoint in hardhat-config. 

Once you have pasted your private key and contract address in the .env file, simply run command 

```shell
node index.js
```

and go to http://localhost:3000 to interact with the decentralized voting application.

