# Dependencies

[Jevko CLI](https://github.com/jevko/jevko-cli) must be installed to publish this extension.

# Editing the syntax file

DO NOT EDIT THE jevkoml.tmLanguage.json syntax file. Instead edit jevkoml.jevkodata and then convert it by running:

```
jevko syntaxes/jevkoml.jevkodata
```

This is done automatically on extension publish and before launching the extension for debugging (F5).