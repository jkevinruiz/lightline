# lightline

Source the created snapshot in tmux.conf
```
# in tmux.conf
source-file [file]

# alternatively, check file exists before sourcing it in tmux.conf
if-shell "test -f [file]" "source [file]"
```
