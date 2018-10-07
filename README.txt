Mirar esto
==========

https://github.com/sickill/vim-monokai

http://vimcolors.com/


Pasos:
------
1) Crear directorio ".vim/colors/":
    mkdir -p ~/.vim/colors/

2) Copiar el archivo "monokai.vim" al directorio ".vim/colors/"
    cp monokai.vim ~/.vim/colors/

3) Copiar el archivo "vimrc" al HOME:
    cp vimrc ~/.vimrc


Ejemplo de archivo VIMRC
------------------------

" Show line numbers
set number

" https://stackoverflow.com/questions/1675688/make-vim-show-all-white-spaces-as-a-character
" Show white space
:set listchars=tab:>>,space:.
:set list

" https://stackoverflow.com/questions/234564/tab-key-4-spaces-and-auto-indent-after-curly-braces-in-vim
" Set tab space = 4
" show existing tab with 4 spaces width
set tabstop=4
" when indenting with '>', use 4 spaces width
set shiftwidth=4
" On pressing tab, insert 4 spaces
set expandtab



Desactivar numero de lineas:
    :set nu!
