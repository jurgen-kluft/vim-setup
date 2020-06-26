# vim-setup

My neovim dot files.
The `init.vim` file is saved to [init.vim](https://github.com/jurgen-kluft/vim-setup/blob/master/init.vim).

**Table of Contents**

<!-- toc -->

- [vim-setup](#vim-setup)
  - [About](#about)
    - [Installing](#installing)
    - [Vim-Plug](#vim-plug)
  - [Contributing](#contributing)
    - [Using the `Makefile`](#using-the-makefile)

<!-- tocstop -->

## About

### Installing

Just run the following commands via terminal to get perfectly set up:

```console
$ cd ~/
$ git clone --recursive https://github.com/jurgen-kluft/vim-setup.git .vim
$ ln -sf $HOME/.vim/init.vim $HOME/.config/nvim/init.vim
$ cd $HOME/.vim
```

### Vim-Plug

The vim dot files make use of the excellent [vim-plug](https://github.com/junegunn/vim-plug) vim path manager to install plugins and runtime files into their own private directiories.

Currently using version 0.10.0 of vim-plug.

## Contributing

### Using the `Makefile`

You can use the [`Makefile`](Makefile) to run a series of commands.

```console
$ make help
install                        Sets up symlink for user and root .vimrc for vim and neovim.
README.md                      Generates and updates plugin info in README.md.
update-vimplug                 Updates vim-plug
update                         Updates vim-plug and all plugins.
```
