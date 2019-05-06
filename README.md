# dotFiles
My configuration files for bash, zsh, git and more.

## redlight
Add redlight config. Auto update color.

## zsh
Using powerlevel9k

## git
A set of alias and other usefull configuration

## tmux

- `C-h/j/k/l` - switch to pane in the given direction
- `C-\\` - toggle between last active panes

Under tmux prefix `C-a`:

- `C-l` - clear terminal
- `S` - switch to a session that starts with given name, or switch to the last
  session if no name given
- `m` - open man page in a vertical split
- `g` - tail `log/development.log` in a new window
- `R` - source `~/.tmux.conf` after changes

My tmux keybindings:

    _ vertical split (by default is %)
    - horizontal split (by default is ")
    ! break pane into new window
    c new window
    
    o select next pane
    { swap pane with previous
    } swap pane with next
    n next window
    p previous window
    ) next session
    ( previous session
    ; select previously active pane
    l select previously active window
    
    s interactive session & window browser
    w interactive window browser
    
    $ rename session
    , rename window
    
    : command prompt
    d detach
    f search text in open windows
    
    [ copy mode
    ] paste buffer
    # list buffers
    - delete buffer

It's also possible to use the mouse and move between panes using ALT and the arrows.

## Transparent taskbar
To make the taskbar transparent, choose the diresed theme to be used, then open to `/usr/share/themes/Linux\ Mint/cinnamon.css` and add `background-color: rgba(0,0,0,0);` to **#panel**. Save and change the theme (for the same theme, just to update). If you see a shadow, comment out everything that starts with *#panel* and has a `*-gradient-*` property.