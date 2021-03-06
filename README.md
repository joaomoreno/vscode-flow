# Flow for Visual Studio Code

![https://i.imgur.com/4rNERMs.png](https://i.imgur.com/4rNERMs.png)

This extension adds [Flow](http://flowtype.org) support for VS Code. Flow is a static type checker, designed to find type errors in JavaScript programs.

## Installation

Follow the [instructions](https://code.visualstudio.com/docs/editor/extension-gallery) for VS Code extension installation.

## Setup

* Flow is only supported on Mac and Linux, follow [flowtype.org](http://flowtype.org/docs/getting-started.html#_) to get started
* You need a `.flowconfig` in your workspace to enable the flow features
* Make sure you are able to run the `flow` command from the command line
* Set workspace preference with `"javascript.validate.enable": false`.

**Flow does not support Windows, you can follow this Github issue https://github.com/facebook/flow/issues/6**

## Workspace settings

flow comes bundled with this extention. if you would like to use 
a different version of flow, use `"flow.path": "/path/to/wher/you/put/flow"` in your `.vscode/settings.json` file.

You can disable the flow plugin using `"flow.disable": true` in your `.vscode/settings.json` file.

## Features

* Syntax Coloring
* IntelliSense
* Go to Definition / Peek Definition
* Diagnostics (Errors, Warnings)

## Disable

You can disable `flow` per workspace by setting `"flow.disable": true` in your `.vscode/settings.json` file.

## Known Issues

* You should set workspace preference to disable default syntax validation from Visual Studio Code: `"javascript.validate.enable": false`.

## Contributing

* please refer to [CONTRIBUTING.md](CONTRIBUTING.md)

## License
[See here](LICENSE)
