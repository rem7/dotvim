
git clone git@github.com:rem7/dotvim.git ~/.vim

ln -s ~/.vim/vimrc ~/.vimrc


```
To add a vimplugin to pathogen

git subtree add --prefix bundle/vim-golang https://github.com/jnwhiteh/vim-golang.git master --squash

To update said module

git subtree pull --prefix bundle/vim-golang https://github.com/jnwhiteh/vim-golang.git master --squash
```
