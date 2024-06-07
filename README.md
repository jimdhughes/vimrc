1.  Installation:

```terminal
git clone git://github.com/nelstrom/dotvim.git ~/.vim
```

2. Create symlinks:

```terminal
    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc
```

3. Switch to the `~/.vim` directory, and fetch submodules:
```terminal
    cd ~/.vim
    git submodule init
    git submodule update
```
