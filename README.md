## Introduction

`compile-mode.nvim` is a Neovim plugin which emulates the features of Emacs' `Compilation Mode`. It allows you to run commands which are output into a special buffer, and then rerun that command over and over again as much as you need. See [Emacs Compilation Mode](https://www.gnu.org/software/emacs/manual/html_node/emacs/Compilation-Mode.html) for more details.

## Installation

Use your favorite plugin manager. `compile-mode.nvim` depends on [plenary.nvim](https://github.com/nvim-lua/plenary.nvim).

Here's an example of a [Lazy](https://github.com/folke/lazy.nvim) config for `compile-mode.nvim`:

```lua
return {
  "ej-shafran/compile-mode.nvim",
  branch = "latest",
  -- or a specific version:
  -- tag = "v3.0.0"
  dependencies = { "nvim-lua/plenary.nvim" },
  opts = {}
}
```

## Contributing

Contributions are welcome in the form of GitHub issues and pull requests.

For contributing details see [CONTRIBUTING.md](CONTRIBUTING.md).

<!-- panvimdoc-ignore-end -->
