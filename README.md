# VS Code Chptr Markdown Grammar

VS Code chptr markdown extension's Textmate grammar.  Based on Microsoft's VS Code Markdown extension.

# Contributing
The main grammar is stored in `syntaxes/markdown.tmLanguage`. This file is generated from `markdown.tmLanguage.base.yaml`:

## Building
To generate the main grammar:

```bash
$ npm install
$ npm run build 
```

## Testing
To run the grammar tests:

```bash
$ npm run test
```

The test cases are stored as markdown files under `test/colorize-fixtures`. Grammar test results are stored under `test/colorize-results`, which are automatically generated from the fixtures.

To test the grammar in VS Code, select the `Launch Extension` configuration in the VS Code debugger and run.

