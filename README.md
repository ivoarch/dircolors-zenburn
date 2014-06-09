Zenburn 256 color scheme for the color GNU ls utility.
-------------------------------------------------

Install
-------

1. Copy or link `dircolors` file to `~/.dir_colors`
2. Put something like this in your shell resource file: `eval $( dircolors -b $HOME/.dir_colors )`
3. To use the colors add the `--color` switch to the invocation of LS or DIR.

Example
-------

Add the following three lines to your `~/.bashrc` or `~/.zshrc` file:

    eval $( dircolors -b $HOME/.dir_colors )
    alias dir='dir --color'
    alias ls='ls --color'

Screenshot
----------

![screenshot](https://github.com/ivoarch/dircolors-zenburn/raw/master/img/screenshot.png)
