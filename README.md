# regular-table

[![Build Status](https://travis-ci.org/jpmorganchase/regular-table.svg?branch=master)](https://travis-ci.org/jpmorganchase/regular-table)

## Installation

Add to your project via `yarn`:

```bash
yarn add regular-table
```

Import into your asset bundle.  `regular-table` exports no symbols, only the
`<regular-table>` Custom Element it registered as a module side-effect:

```javascript
import "regular-table";
```

## Development

First install `dev_dependencies`:

```bash
yarn
```

Build the library

```bash
yarn build
```

Run the test suite

```bash
yarn test
```

Start the example server at [`http://localhost:8080/examples/`](http://localhost:8080/examples/)

```bash
yarn start
```