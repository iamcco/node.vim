# Cspell Vim Language Dictionary

Vim Language dictionary for cspell.

This is a pre-built dictionary for use with cspell.

Supports keywords of (Neo)vim

This dictionary is included by default in cSpell.

## Installation

Global Install and add to cspell global settings.

```sh
npm install -g cspell-dict-vimlang
cspell-dict-vimlang-link
```

## Uninstall from cspell

```sh
cspell-dict-vimlang-unlink
```

## Manual Installation

The `cspell-ext.json` file in this package should be added to the import section in your cspell.json file.

```javascript
{
    // …
    "import": ["<path to node_modules>/cspell-dict-vimlang/cspell-ext.json"],
    // …
}
```

## Building

I's only necessary if you want to modify the contents of the dictionary.
Note: Building will take a few minutes for large files.

```sh
npm run build
```
