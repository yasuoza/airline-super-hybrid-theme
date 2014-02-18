# airline-super-hybrid-theme

This repository demonstrates that you can use custom [vim-airline](https://github.com/bling/vim-airline) theme.

## Configuration

Create following directory structure

```
custom-theme-directory
└── autoload
    └── airline
        └── themes
            └── mine.vim

3 directories, 2 files
```

Then edit `mine.vim` what ever you want. You can refer to [lucius theme](https://github.com/bling/vim-airline/blob/master/autoload/airline/themes/lucius.vim).
You should set same name theme name `airline#themes#__theme_name__#palette`.
In above case, `airline#themes#mine#palette`.

## Instllation

```vim
NeoBundle 'bling/vim-airline'
NeoBundle 'yasuoza/airline-super-hybrid-theme'
let g:airline_theme='super_hybrid'
```

## LICENSE

* [vim-airline](https://github.com/bling/vim-airline)
MIT License. Copyright (c) 2013-2014 Bailey Ling.

* [vim-hybrid](https://github.com/w0ng/vim-hybrid/)

* airline-super-hybrid-theme
MIT License. Copyright (c) 2014 Yasuharu Ozaki

