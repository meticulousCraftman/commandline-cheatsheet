# Cheatsheet

## Index
  - [tmux](#tmux)
  - [vim](#vim) -> Text editor
  - [exa](#exa) -> Replacement for `ls`
  - [bat](#bat) -> Replacement for `bat`
  - [rg](#rg) -> Replacement for `grep`
  - [fx](#fx) -> JSON document viewer
  - [cargo](#cargo) -> Rust Lang
  - [go](#go)-> Go Lang
  - [countdown](#countdown) -> Countdown timer in Go
  - [fish](#fish) -> Fish shell, replacement for `bash`
  - [nodejs](#nodejs)
  - [npm](#npm)
  - [npx](#npx) -> Run npm packages without installing them globally.

### tmux
Terminology:
  - `C-` : Control Key
  - `M-` : Meta Key / Alt
  - `S-` : Shift Key
  
Commands:
  - `tmux new` , `tmux new -s sessionname`, `tmux new-session` -> Create a new session
  - `C-b` -> Tmux prefix (Crtl + b)
  - `C-b ?` -> Help Key
  - `C-b:neww` -> Create a new window
  - `C-b:<command>` -> Type commands at interactive prompt
  - `C-b:<command1>;<command2>;<command3>` -> For command sequence
  - `C-b d`, `C-b:detach` -> Detach from current session and let it run in background.
  - `tmux attach` -> Attach to tmost recently used session
  - `tmux attach -t mysession` -> Attach to session named mysession
  - `tmux new -As mysession` -> Attach to a session named "mysession" if it exists, otherwise create a new one.
  - `tmux ls` -> To list sessions
  - `tmux kill-server`, `C-b: kill-server` -> Kill tmux server
  - `C-b c`, `C-b:new-window`, `C-b:neww` -> Create a new window
  - `C-b:neww -dn <name>` -> Create a new window in background, don't switch to it.
  - `C-b:neww -t 10` -> Create new window with index 10
  - `C-b:neww <command>` -> Create a new window and execute <command> in it.
  - `C-b:neww top` -> Create a new window and execute "top" in it.
  - `C-b %` -> Split the window on vertical plane, **left** and **right**.
  - `C-b % "` -> Split window horizontally, **top** and **bottom**
  - `C-b:split-window` -> Split current window
    - `-h` -> Vertical split, **left** and **right**
    - `-v` -> Horizontal split, **top** and **bottom**
    - `-d` -> Does not change newly created pane to active pane
  - `C-b 0` -> Change to window index 0
  - `C-b '` -> Ask for a window index and changes to that window
  - `C-b n` -> Next window
  - `C-b p` -> Previous window
  - `C-b l` -> Last window
  - `C-b <Up>`, `C-b <Down>`, `C-b <Right>`, `C-b <Left>` -> Change active panes
  - `C-b q` -> Show pane numbers for a short time
  - `C-b q 1` -> Change to pane number 1
  - `C-b o` -> Move to next pane
  - `C-b s` -> Show all sessions in tree mode collapsed, use <Up>, <Down>, <Right>, <Enter> keys to select and navigate
  - `C-b w` -> Starts sessions expanded with windows
  - [Tree mode] `q` -> Quit in tree mode

### vim
Commands for vim

### exa
Commands for exa

### bat
Commands for bat

### rg
Commands for rg

### fx
Commands for fx
