---
title: colony-starter-angular
section: Starters
order: 3
---

_A boilerplate to get started with [colonyJS](https://github.com/JoinColony/colonyJS) using Angular!_

## Prerequisites

- Node `>=10.13.0`
- Yarn `>=1.12.0`
- Docker `>=18.09.0`

_You may find it helpful to use Node Version Manager (`nvm`) to manage Node versions._

_If you are using Linux, check out [Linux Setup](/colonystarter/docs-linux-setup/) to ensure Yarn and Docker are set up accordingly._

## Installation

Globally install the [colony-cli](/colonystarter/cli-colony-cli) package.

```
yarn global add @colony/colony-cli
```

Install the `colony-starter-angular` package.

```
colony build colony-starter-angular
```

Alternatively, you can use [npx](https://www.npmjs.com/package/npx) and kickstart the `colony-starter-angular` package in one line without having to globally add the [colony-cli](/colonystarter/cli-colony-cli) package:

```
npx -p @colony/colony-cli colony build colony-starter-angular
```

## Start Network

Open a new terminal window and start [Ganache](https://github.com/trufflesuite/ganache-cli):

```
yarn start-ganache
```

## Deploy Contracts

Open a new terminal window and deploy the [colonyNetwork](https://github.com/JoinColony/colonyNetwork) contracts:

```
yarn deploy-contracts
```

## Start TrufflePig

Once the contracts have been deployed, start [TrufflePig](https://github.com/JoinColony/trufflepig):

```
yarn start-trufflepig
```

## Seed Network

Open a new terminal window and run the seed network script:

```
yarn seed-network
```

## Colony Setup

Once the network has been seeded, run the colony setup script:

```
yarn colony-setup
```

## Start Server

Once your test colony has been set up, start the development server:

```
yarn start
```

## Open Browser

Open your browser and start building:

[http://localhost:4200](http://localhost:4200)

## Run Tests

Open a new terminal window and run the example tests:

```
yarn test
```
