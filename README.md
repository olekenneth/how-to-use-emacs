# How to use Emacs
Gathering of often used emacs commands

Shortcut | Explanation
--- | ---
`C-x` | this means hold **Control** and push **x**
`M-w` | this means hold **Meta** and push **w**

Meta is sent by the terminal and is setup differently from terminal to terminal. In cases where terminal doesn't send meta, you have to tap once at escape to send meta-command, so no need to hold it down. In e.g. iTerm2 you have to set option-key to send meta.

# Basic shortcuts
Shortcut | Command
--- | ---
`C-x C-c` | Exit
`C-x C-s` | Save
`C-x C-f` | Open

# Cursor movement
Shortcut | Command
--- | ---
`C-f` | Move cursor forward
`C-b` | Move cursor backward
`C-n` | Move cursor down
`C-p` | Move cursor up
`C-n` | Move cursor down
`M-<` | Jump to start of buffer
`M->` | Jump to end of buffer
`C-v` | Scroll page down
`M-v` | Scroll page up

# Buffer managament
Shortcut | Command
--- | ---
`C-x b` | Jump to different open buffer
`C-x C-b`| Open ibuffer (to see open buffers)
`C-x k` | Kill buffer

# Window managament
Shortcut | Command
--- | ---
`C-x 2` | Split window horizontally
`C-x 3` | Split window vertically
`C-x 1` | Only show current window
`C-x 0` | Close current window

# Selection and copy/paste
Shortcut | Command
--- | ---
`C-space` | Start selection
`C-w` | Cut selection
`M-w` | Copy selection
`C-y` | Paste copy
`C-y M-y M-y` | Change paste to previous paste (cycle with `M-y`)
`C-x h` | Select all text in buffer

## Version control
Shortcut | Command
--- | ---
`C-x v d` | Open version control directory
`m` | Mark file
`u` | Unmark file
`i` | Add unregistered file
`+` | Update file (or directory)
`g` | Refresh view
`C-x v v` | Commit marked files
`C-c C-c` | Send commit (and push)

# My customization
* 4 spaces instead of tabs
* `color-theme-sanityinc-tomorrow-day`-theme
* Helm and Projectile
* Rebind `C-x C-f` to use Projectile find-file


## org-mode
Create a file (for ex. TODO.org). Open the file and run `org-agenda-file-to-front` or `C-c [`

| Command     | Desciption               |
|-------------|--------------------------|
| `C-c a a`   |  Open org-mode agenda
| `C-c a t`   |  List all TODOs
| `C-c a g`   |  GTD (Getting Things Done®)-view



### On a task

| Command      | Desciption               |
|--------------|--------------------------|
| `C-c C-t`    | Change state 
| `C-u C-c C-t`| Change state and add note
| `C-c C-d`    | Add deadline date to task
| `C-c C-s`    | Add schedule date to task
| `C-c C-c`    | Fix timestamp 
