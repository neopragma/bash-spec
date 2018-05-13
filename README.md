# Unit test framework for bash

## Unit test framework using a BDD style syntax.

* bash_spec - source this file at the top of your test script.
* test_spec - unit tests for bash_spec.

## Samples

* fizzbuzz-bash - sample 'application' to illustrate unit testing.
* fizzbuzz-test - sample test script for fizzbuzz-korn.
* phone-bash - sample 'application' to illustrate unit testing.
* phone-test - sample test script for phone-korn.
* install-test - simple validation that packages are installed and have the expected permissions.

## Install

```shell
curl -O https://raw.githubusercontent.com/neopragma/bash-spec/master/bash_spec
```

Note the project name has a dash while the script itself has an underscore (for your amusement and convenience).

## Convenience

Add pwd to PATH:

```shell
. ./envvars
```

Wrapper script to run tests:

```shell
run install-test
```

```shell
run all
```
