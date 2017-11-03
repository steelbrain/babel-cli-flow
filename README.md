# Babel-CLI-Flow

Babel-CLI-Flow is a fork of the Babel CLI v6.24.1. No changes have been made other than that it also saves the contents of the source file with a `.flow` extension. This utility creates a hard link for files so if the source `.flow` files are modified, the same changes will also be applied to the source ones (except deleting, the real source files will not be deleted when you delete the linked `.flow` ones).

## Usage

The CLI parameters and everything are fully in line with that of the original `babel-cli` so this package is a drop-in-replacement.

```
$ babel-flow src --out-dir lib
$ babel-flow src --out-dir lib --watch
```

## License

This project is licensed under the terms of MIT LICENSE. See the LICENSE file for more info.
