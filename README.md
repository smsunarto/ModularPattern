# Lattice Solidity Starter

A highly opinionated Solidity starter repository.

- Testing boilerplate
- Linting (Prettier & Solhint) configurations
- Text editor configuration (VS Code & `.editorconfig`)
- CI: Run Foundry tests
- CI: Run Prettier + Solhint with autofix

## Getting Started

To usage Lattice Solidity Starter, click the "Use this template" button on this repository page.

**Install Foundry**

```
curl -L https://foundry.paradigm.xyz | bash
foundryup
```

**Install Development Dependencies**

```
yarn
```

**VS Code Extensions**

This repository comes with a set of recommended extensions for Solidity development that will (hopefully) make your life easier.

To see it, press `CMD + SHIFT + P` on VS Code and type "Show Recommended Extensions".

## Usage

**Forge: Fetch libraries**

If you forgot to clone the git repository recursively, you will neeed to run this command to fetch the Solidity library dependencies in `/lib`.

```
yarn fetch
```

**Forge: Update libraries**

```
yarn update
```

**Forge: Build**

```
yarn build
```

**Forge: Run tests**

```
yarn test
```

**Forge: Run tests with logs**

```
yarn trace
```

**Forge: Clean artifacts**

```
yarn clean
```
