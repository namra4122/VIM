# VIM

## Modes in VIM:

- `NORMAL` : Move the Cursor
- `INSERT` : Type and Insert new lines, text, whatever
- `VISUAL` : Move the Cursor and it will select/highlight the lines
- `: aka CMD` : Type all kind of cmds (For e.g. :w)

## MOVEMENTS:

- `j` : Move cursor down
- `k` : Move cursor up
- `h` : Move cursor left
- `l` : Move cursor right
- `w` : Move to start of the next word
- `e` : MOve to end of the next word
- `b` : Backtrack to start of the next work <br>
  [TIP - Can use number for multiple line. Example: `5k` to move 5 line up]

## INSERT MODE

- `I` : Enter to Insert mode
- `O` : Enter the Insert mode in new Line
- `A` : Enter the Insert mode on right of the cursor
- `SHIFT + I` : Enter the Insert mode in start of the line
- `SHIFT + A` : Enter the Insert mode in end of the line
- `SHIFT + O` : Enter the Insert with new line on above of the current line
- `Esc` : Enter to Normal Mode

## VISUAL MODE

- `V` : Enter to Visual mode
- `u` : Undo
- `CMD + r`: Redo
- `d`: Delete
- `y` : Copy
- `p` : Paste
- `c` : Delete the selected text and Enter to Insert Mode
- `cc` : Delete the content of that line and Enter to Insert Mode

## `:` CMDs

- `:q` : Quit
- `:w` : Write the file
- `:wq` : Write and Quit the file
- `:set number` : Activate line number
- `:set relativenumber` : Activate the relative line number

- `dd` : Delete whole line
- `yy` : Copy whole line
- `P` : Paste above the cursor line
