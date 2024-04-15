# dart-package-template

A reusable template repository for standalone Dart packages.

[![Github Actions](https://github.com/matanlurey/dart-package-template/actions/workflows/check.yaml/badge.svg)](https://github.com/matanlurey/dart-package-template/actions/workflows/check.yaml)
[![Coverage Status](https://coveralls.io/repos/github/matanlurey/dart-package-template/badge.svg?branch=main)](https://coveralls.io/github/matanlurey/dart-package-template?branch=main)

```shell
git clone https://github.com/matanlurey/dart-package-template . && rm -rf .git && git init
```

## Usage

```dart
import 'package:dart-package-template/dart-package-template.dart';
```

## Features

TODO: Document what the package does, include screenshots, etc.

## Contributing

If you have a feature you'd like to see, feel free to
[file an issue][gh-issues-new] or [fork and open a pull request][gh-fork].

[gh-issues-new]: https://github.com/matanlurey/dart-package-template/issues/new
[gh-fork]: https://github.com/matanlurey/dart-package-template/fork

### CI

This package is:

- Formatted with `dart format`.
- Checked with `dart analyze`.
- Tested with `dart test`, including with code coverage.

See [`github/workflows/check.yaml`](./.github/workflows/check.yaml) for details.

### Coverage

To view the coverage report locally (MacOS):

```shell
brew install lcov
dart run coverage:test_with_coverage
genhtml coverage/lcov.info -o coverage/html
open coverage/html/index.html
```
