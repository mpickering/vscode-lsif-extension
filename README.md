# Extension to run a language server from a Language Server Index Format file

This extension checks if a lsif.json file exists in the root of a workspace folder and if so server a language server from the content of the lsif.json file.

How to use this.

```
# Install vsce tool
npm install vsce
# Install package dependencies
npm install
# Create the vsix package
node_modules/vsce/out/vsce package

# Enable proposed api in vscode
code{-insiders} --enable-proposed-api ms-vscode.lsif

# Install the vsix file from the extensions menu
```

