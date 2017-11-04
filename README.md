# myhelp.vim

A vim plugin that holds a custom cheatsheet for me. Idea lifted from [this article on TechnoSophos][original-idea].

## Installation

### Using [Vundle][vundle]:

Just add this line to your `~/.vimrc`:

```vim
Plugin 'ianchesal/myhelp.vim'
```

And run `:PluginInstall` inside Vim.

### Using [pathogen.vim][pathogen]:

Copy and paste in your shell:

```bash
cd ~/.vim/bundle
git clone https://github.com/ianchesal/myhelp.vim.git
```

### Using [vpm][vpm]:

Run this command in your shell:

```bash
vpm insert ianchesal/myhelp.vim
```

### Using [Plug][plug]:

Just add this line to your `~/.vimrc` inside plug call:

```vim
Plug 'ianchesal/myhelp.vim'
```

And run `:PlugInstall` inside Vim or `vim +PlugInstall +qa` from shell.

## License

Apache License 2.0

[original-idea]: http://technosophos.com/2014/10/09/create-built-in-vim-cheatsheet.html
[pathogen]: https://github.com/tpope/vim-pathogen
[txt-doc]: https://raw.githubusercontent.com/rizzatti/dash.vim/master/doc/dash.txt
[vpm]: https://github.com/KevinSjoberg/vpm
[vundle]: https://github.com/gmarik/vundle
[plug]: https://github.com/junegunn/vim-plug
