#'base16 bright dark' syntax theme for the fish shell

## base16?

[base16](https://github.com/chriskempson/base16) is a collection of colour schemes for many applications, including terminal emulators.

[base16-shell](https://github.com/chriskempson/base16-shell) provides a neat method of applying one of these schemes to a terminal running the fish shell.

1. run `git clone https://github.com/chriskempson/base16-shell.git ~/.config/base16-shell`
2. add the line `eval sh $HOME/.config/base16-shell/base16-bright.dark.sh` to `config.fish`

In step 2, one can change `base16-bright.dark` to one's base16 theme of choice.

## syntax theme

The author's choice of terminal theme is `base16-bright.dark`. Applying this theme, however, does not change the **syntax theme** of fish shell; that is, the colours of different components of code (commands, parameters, comments, etc). Since these colours are determined separately, they may not match up well with the main theme.

The **base16 bright dark fish syntax theme** is simply a conversion of the default fish syntax theme to colours in the 'base16 bright' palette. To apply, add the lines from the file `base16-bright.dark-fish-syntax-theme` (found above) to `config.fish`.
