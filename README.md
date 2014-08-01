Antigen Plugins and Themes
==========================

This repository is a directory for ZSH plugins and themes supported by [antigen](https://github.com/zsh-users/antigen).

You are welcome to submit Pull Requests for more plugins and themes.

How to install
==============
1. Install antigen as exlained [here](https://github.com/zsh-users/antigen).
2. Setup `.zshrc` file as explained below.
3. Add to the `.zshrc` file any plugin and theme you wish to use.

Setup `.zshrc` file (copy from antigen readme)
==============================================
The usage should be very familiar to you if you use Vundle. A typical `.zshrc` might look like this:

    source /path-to-antigen-clone/antigen.zsh

    # Load the oh-my-zsh's library.
    antigen use oh-my-zsh

    # Bundles from the default repo (robbyrussell's oh-my-zsh).
    antigen bundle git
    antigen bundle heroku
    antigen bundle pip
    antigen bundle lein
    antigen bundle command-not-found

    # Syntax highlighting bundle.
    antigen bundle zsh-users/zsh-syntax-highlighting

    # Load the theme.
    antigen theme robbyrussell

    # Tell antigen that you're done.
    antigen apply


Plugins
=======
* [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting): antigen bundle zsh-users/zsh-syntax-highlighting
* [Oh-My-Zsh plugins](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins-Overview): antigen bundle <plugin name>

Themes
======
* [Oh-My-Zsh themes](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes): antigen theme <theme name>
