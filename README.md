Dollar Sign
=============================

For when you accidentally copy the dollar sign and your shell returns "$: command not found".

## Installation

Add the executable to your path and give it permissions.

```
sudo printf '#!/bin/sh\nexec "$@"\n' > /usr/local/bin
sudo chmod +x /usr/local/bin/$
```

Or to install using [`npm`](https://www.npmjs.com/):

```
npm -g install @fraction/dollar-sign
```

## Usage

Use the dollar sign or don't use the dollar sign – it doesn't matter at all.

```sh
$ echo "Hello world"
# Hello world

$ $ $ $ $ $ $ echo "Hello world"
# Hello world
```

## Support

Please [open an issue](https://github.com/fraction/dollar-sign/new) for questions and concerns.

## Contributing

Fork the project, commit your changes, and [open a pull request](https://github.com/fraction/dollar-sign/compare/).
