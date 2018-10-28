# fzy-fd-zsh-shortcut
Makes ^S start fzy with fd for file searching in zsh. It also respects your current command line, so if you already typed `vim ~/`, it will only search for files in your home directory.

Based on the examples from [https://github.com/garybernhardt/selecta/blob/master/EXAMPLES.md#zsh-insert-fuzzy-found-paths-directly-into-the-shell-command-line](https://github.com/garybernhardt/selecta/blob/master/EXAMPLES.md#zsh-insert-fuzzy-found-paths-directly-into-the-shell-command-line) and the code from [https://github.com/junegunn/fzf/blob/master/shell/key-bindings.zsh](https://github.com/junegunn/fzf/blob/master/shell/key-bindings.zsh).
