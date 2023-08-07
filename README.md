# mdbook nb Plugin

This plugin add two commands to `nb` for initialize and run a server in a notebook via `mdbook`

# You will need

- Rust
- mdbook
- nb

# Installation

```bash
nb plugins install https://raw.githubusercontent.com/miguehm/mdbook-nb/main/mdbook.nb-plugin
```

# How to use

Initialize a mdbook inside a notebook

```bash
nb initbook
```

Run a server in the current notobook

```bash
nb servebook
```
