# dot-vim

## About
Here's my collection of `~/.vim` files powered by pathogen. Each bundle is a git submodule, making it easy to stay up-to-date with upstream changes.

## Installation

On a fresh machine without `~/.vim`, use the following clone command:

`````
$ git clone --recursive git://github.com/iphoting/dot-vim.git ~/.vim
$ ln -s ~/.vim/.vimrc ~/.vimrc
`````

Alternatively:

`````
$ git clone git://github.com/iphoting/dot-vim.git ~/.vim
$ cd ~/.vim
$ git submodule update --init
$ ln -s ~/.vim/.vimrc ~/.vimrc
`````

If you already have a `~/.vim` directory, consider manually integrating using symlinks.

## Credits
All credits go to the respective authors.