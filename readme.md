## Thesis - Private Blockchain

This is one out of four repositories that cover the project created for my bachelors thesis. Briefly summarized, this project allows an Internet of Things (IoT) device to be managed indirectly via a smart contract on the Ethereum blockchain. IoT devices are able to function autonomously through a custom written middleware that interprets payloads received from the blockchain and converts them into actions. The usage of the system is streamlined through a react-based distributed frontend application.

**The projects repositories**:

| Name          | Repository    |
| ------------- |:-------------:|
| Smart Contract Backend      | [https://github.com/wickstjo/oracle-manager](https://github.com/wickstjo/oracle-manager) |
| Middleware Interpreter      | [https://github.com/wickstjo/oracle-manager](https://github.com/wickstjo/iot-manager) |
| Frontend Application        | [https://github.com/wickstjo/distributed-task-manager](https://github.com/wickstjo/distributed-task-manager)|
| Private Blockchain          | [https://github.com/wickstjo/thesis-chain](https://github.com/wickstjo/thesis-chain) |

## Content

This repository contains a blockchain database that was generated with [Geth](https://geth.ethereum.org/). The blockchain mimics the actions of the Ethereum mainnet and has ready generated user keys listed in the **keystore directory**. After installing Geth, the blockchain can be launched with the **run.sh script** located in the root directory.