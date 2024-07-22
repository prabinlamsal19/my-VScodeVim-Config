# Enhancing Developer Experience with VSCode Vim Extension and Keybindings

Using the VSCode Vim extension paired with customized keybindings can significantly enhance your development workflow, offering a smoother and faster experience compared to using Neovim. This approach not only reduces the learning curve and setup time but also boosts efficiency.

## Vim Motion Shortcuts (in Vim Mode)
- `leader f` - Global search
- `leader v`, `s` - Vertical, horizontal split
- `leader h,j,k,l` - Switch between panes the Vim way
- `leader i` - Go to implementation
- `>`, `<` - Shift line right, left
- `Shift + j` - Move line above
- `]` or `[` + `d` - Move to the next or previous error/warning marker
- `leader d` - Go to definition

Plus, enjoy all the smooth shortcuts of Vim motions.

## Navigation Shortcuts (Vim Unrelated)

### VSCode Terminal
- `Ctrl + m` - Open/close terminal window
- `Ctrl + n` - New terminal
- `Ctrl + d` - Delete/kill opened terminal
- `Ctrl + j,k` - Switch between terminals the Vim way

### File Explorer
- `Ctrl + i` - Go to file explorer (from active text editor) / Go to active text editor (from any place else e.g., explorer, terminal)
- `Ctrl + b` - Close the file explorer window
- `Ctrl + Space`, `Enter` - Preview file, Open file and go inside
- `Ctrl + j`, `k` - Move up, down the file tree
- `Ctrl + N`, `n`, `d`, `r` - Create new folder, new file, delete file/folder, rename file/folder
- `Ctrl + o` - Switch control between terminal and active text editor

## Drawbacks
- Less impact on others because of your normie VSCode IDE no matter how fast you are. Recommended to use with highly riced arch to account for the disadvantage.
- Missing global mark functionality

## Contributions Needed
- Adding debugger on selected lines
- Better shortcuts for go-to-definition and related actions
- Ability to change the code action menu items with Vim motions
- Switching between problems, debug console, test, comments, outputs tab, etc.
- Any other improvements you find suitable

## Recommended Layout
Place your terminal and debug console in the same window. Note that we can't switch between them with this setup.

Feel free to contribute to make this setup even better!
