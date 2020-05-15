# Signatory Core

A transaction and message signer for the Ethereum Stack.

## Installation

`npm install @etclabscore/signatory-core --save`

## Usage

```
import { methods as signatoryFactory, MemoryStorage } from "@etclabscore/signatory-core";


const signatoryCore = signatoryFactory(new MemoryStorage());

const run = await () => {
  const accounts = await signatoryCore.listAccounts();
  console.log("accounts: ", accounts);
}

run();
```

### Contributing

How to contribute, build and release are outlined in [CONTRIBUTING.md](CONTRIBUTING.md), [BUILDING.md](BUILDING.md) and [RELEASING.md](RELEASING.md) respectively. Commits in this repository follow the [CONVENTIONAL_COMMITS.md](CONVENTIONAL_COMMITS.md) specification.
