# Hackathon Starter

This is a simple starter project that demonstrates how to use [colonyJS](https://github.com/JoinColony/colonyJS) (a JavaScript client for [colonyNetwork](https://github.com/JoinColony/colonyNetwork)). This project is set up to start a local test network using [Ganache](https://github.com/trufflesuite/ganache-cli) and then deploy the [colonyNetwork](https://github.com/JoinColony/colonyNetwork) contracts to the local test network using [Truffle](https://github.com/trufflesuite/truffle). This project also uses [TrufflePig](https://github.com/JoinColony/trufflepig) to find and read the deployed contracts during local development.

This project includes example scripts also found in the [Get Started](https://joincolony.github.io/colonyjs/docs-get-started/) and [Task Lifecycle](https://docs.colony.io/colonyjs/docs-task-lifecycle/) pages of the [colonyJS Docs](https://docs.colony.io/colonyjs/docs-overview). In order to help you hit the ground running with your new project, this starter project includes all of the examples from the docs plus some, and it gives you the opportunity to execute and test those examples with a few simple commands.

## Prerequisites

- Yarn 1.7
- Node 9.5

_You may find it helpful to use Node Version Manager (`nvm`) to manage node versions._

## Install

Move to your working directory and clone the repository:

```
git clone https://github.com/JoinColony/hackathonStarter.git
```

Move to your new project directory:

```
cd hackathonStarter
```

Install the project dependencies:

```
yarn
```

## Development

### Start Network

Open a new terminal window and start a local test network:

```
yarn start-ganache
```

### Deploy Contracts

Open a new terminal window and deploy the colonyNetwork contracts:

```
yarn deploy-contracts
```

### Start TrufflePig

Open a new terminal window and start TrufflePig:

```
yarn start-trufflepig
```

### Run Examples

Open a new terminal window and run the examples:

```
yarn start
```

### Run Tests

Open a new terminal window and run the tests:

```
yarn test
```