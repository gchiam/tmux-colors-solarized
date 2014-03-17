# Solarize color theme tmux configuration

A tmux solarized theme using Ethan Schoonover’s [Solarized color scheme](http://ethanschoonover.com/solarized).

## Repositories
  * This theme as a single repository: [/gchiam/tmux-colors-solarized](https://github.com/gchiam/tmux-colors-solarized)
  * The main solarized repository: [/altercation/solarized](https://github.com/altercation/solarized)

## Installation
These config snippets for the terminal multiplexer tmux should be added to your `~/.tmux.conf` configuration file.
This means you have to append the content of e.g. `tmuxcolors-256.conf` to the end of your own config e.g. by using this oneliner (backup you config first!!):

    cat tmuxcolors-256.conf >> ~/.tmux.conf

In most cases, you have to force tmux to assume the terminal supports 256 colours.
For this, start tmux as `tmux -2`.

This color scheme is tested with tmux >= 1.5. tmux 1.1 is reported as not working.

## Screenshot

### My modification
Here is a screenshot of a tmux session captured from a gnome-terminal using the [Meslo LG M DZ for Powerline font](http://nodnod.net/2009/feb/12/adding-straight-single-and-double-quotes-inconsola/).

![screenshot](https://github.com/gchiam/tmux-colors-solarized/raw/master/tmuxcolors-gchiam.png)

### Original
Here is a screenshot of a tmux session captured from a gnome-terminal using the [dz-version of the awesome Inconsolata font](https://github.com/Lokaltog/powerline-fonts).

![screenshot](https://github.com/gchiam/tmux-colors-solarized/raw/master/tmuxcolors.png)

And another one showing different dircolors from the neighboring [dircolors-solarized](https://github.com/gchiam/dircolors-solarized) repository.

![screenshot](https://github.com/see/dircolors-solarized/raw/master/img/dircolors.256dark.png)
