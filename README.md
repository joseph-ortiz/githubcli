githbucli
=========

a command line that calls out to github

[![Version](https://img.shields.io/npm/v/githbucli.svg)](https://npmjs.org/package/githbucli)
[![CircleCI](https://circleci.com/gh/Code/githbucli/tree/master.svg?style=shield)](https://circleci.com/gh/Code/githbucli/tree/master)
[![Appveyor CI](https://ci.appveyor.com/api/projects/status/github/Code/githbucli?branch=master&svg=true)](https://ci.appveyor.com/project/Code/githbucli/branch/master)
[![Codecov](https://codecov.io/gh/Code/githbucli/branch/master/graph/badge.svg)](https://codecov.io/gh/Code/githbucli)
[![Downloads/week](https://img.shields.io/npm/dw/githbucli.svg)](https://npmjs.org/package/githbucli)
[![License](https://img.shields.io/npm/l/githbucli.svg)](https://github.com/Code/githbucli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g githbucli
$ githbucli COMMAND
running command...
$ githbucli (-v|--version|version)
githbucli/0.0.0 darwin-x64 node-v8.9.4
$ githbucli --help [COMMAND]
USAGE
  $ githbucli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`githbucli hello [FILE]`](#githbucli-hello-file)
* [`githbucli help [COMMAND]`](#githbucli-help-command)

## `githbucli hello [FILE]`

describe the command here

```
USAGE
  $ githbucli hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ githbucli hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/Code/githbucli/blob/v0.0.0/src/commands/hello.ts)_

## `githbucli help [COMMAND]`

display help for githbucli

```
USAGE
  $ githbucli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v1.2.5/src/commands/help.ts)_
<!-- commandsstop -->
