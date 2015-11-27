# vscode-mono-debug
[![build status](https://travis-ci.org/Microsoft/vscode-mono-debug.svg?branch=master)](https://travis-ci.org/Microsoft/vscode-mono-debug)


A simple VS Code debug adapter for the Mono VM based on the [SDB](https://github.com/mono/sdb) command line debugger.

## Building

Building and using VS Code mono-debug requires a basic POSIX-like environment, a Bash-like
shell, and an installed Mono framework.

First, clone the mono-debug project:

	$ git clone https://github.com/Microsoft/vscode-mono-debug

To build the extension vsix, run:

	$ cd vscode-mono-debug
	$ make
