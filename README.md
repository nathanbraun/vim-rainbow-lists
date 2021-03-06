# Introduction

This is a [Vim](http://www.vim.org/) plugin to add rainbow highlighting of indented lists.

  Before | After
  ------ | -----
  ![before](doc/before.png) | ![after](doc/after.png)

# Quick Start

## Installation

If you use [vim-plug](https://github.com/junegunn/vim-plug), then add the
following line to your `vimrc` file:

```vim
Plug 'lervag/vim-rainbow-lists.vim'
```

Or use some other plugin manager:

* [vundle](https://github.com/gmarik/vundle)
* [neobundle](https://github.com/Shougo/neobundle.vim)
* [pathogen](https://github.com/tpope/vim-pathogen)

## Usage

Use the following commands or mappings to enable/disable/toggle the layer
highlighting.

  Command          | Mapping
  -------          | -------
  `:RBListEnable`  | `<plug>(rblist-enable)`
  `:RBListDisable` | `<plug>(rblist-disable)`
  `:RBListToggle`  | `<plug>(rblist-toggle)`

