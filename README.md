
# VIM Library

All of the usefull native vim keybinds.




## Authors

- [@Sysfaz](https://www.github.com/sys-faz)

**NOTE:** Most of the commands can be paired with numbers like: `5h` will go 5 chars left.

## General Commands

| Command  | Description |
|----------|-------------|
| `:w`     | Write to file |
| `:q`     | Quit from file |
| `:wq / :x`     | Write and quit from file |
| `:q!`     | Quit without saving file |
| `.`      | Run the last command |
| `r{char}`| Replace selected character with {char} |
| `x`      | Delete the selected character |
| `u`      | Undo |
| `C+r`    | Redo |
| `zz`     | Center the editor |

## Insert Modes

| Command  | Description |
|----------|-------------|
| `i`      | Insert mode before cursor |
| `a`      | Insert mode after cursor |
| `I`      | Insert mode at the beginning of the line |
| `A`      | Insert mode at the end of the line |
| `o`      | Insert mode creates a new line below the current line |
| `O`      | Insert mode creates a new line above the current line |

## Visual Modes

| Command  | Description |
|----------|-------------|
| `v`      | Visual mode |
| `V`    | Visual line mode |
| `Ctrl+v`    | Visual block mode |

---

## Navigation

| Command    | Description |
|------------|-------------|
| `h`        | Move 1 character left |
| `j`        | Move 1 character down |
| `k`        | Move 1 character up |
| `l`        | Move 1 character right |
| `w`        | Jump to the next word |
| `b`        | Jump to the previous word |
| `e`        | Jump to the end of the word |
| `0`        | Jump to the beginning of the line |
| `$`        | Jump to the end of the line |
| `%`        | Jump to the matching parentheses |
| `t{char}`  | Jump before the next occurrence of {char} |
| `T{char}`  | Jump after the previous occurrence of {char} |
| `f{char}`  | Jump to the next occurrence of {char} |
| `F{char}`  | Jump to the previous occurrence of {char} |
| `gg`       | Jump to the beginning of the file |
| `G`        | Jump to the end of the file |
| `{n}G`     | Jump to line number {n} |

---

## Changing

| Command         | Description |
|-----------------|-------------|
| `c`             | Change selection |
| `cc`            | Change the whole line |
| `C`             | Change the rest of the line from the cursor |
| `cw`            | Change word from the cursor |
| `c{n}w`         | Change {n} words from the cursor |
| `ciw`           | Change the word |
| `ci<' ">`       | Change inside of the <' "> |
| `ci<( { [>`      | Change inside of the <( { [> |
| `ce`            | Change to the end of the word from the cursor |
| `c0`            | Change to the beginning of the line from the cursor |
| `c$`            | Change to the end of the line from the cursor |
| `c%`            | Change the whole block of parentheses |
| `ct{char}`      | Change up until the next {char} |
| `cT{char}`      | Change up until the previous {char} |

---

## Deleting

| Command         | Description |
|-----------------|-------------|
| `d`             | Delete selection |
| `dd`            | Delete the whole line |
| `D`             | Delete the rest of the line from the cursor |
| `dw`            | Delete word from the cursor |
| `d{n}w`         | Delete {n} words from the cursor |
| `diw`           | Delete the word |
| `di<' ">`       | Delete inside of the <' "> |
| `di<( { [>`      | Delete inside of the <( { [> |
| `de`            | Delete to the end of the word from the cursor |
| `d0`            | Delete to the beginning of the line from the cursor |
| `d$`            | Delete to the end of the line from the cursor |
| `d%`            | Delete the whole block of parentheses |
| `dt{char}`      | Delete up until the next {char} |
| `dT{char}`      | Delete up until the previous {char} |

---

## Yanking

| Command         | Description |
|-----------------|-------------|
| `y`             | Yank selection |
| `yy`            | Yank the whole line |
| `yw`            | Yank word from the cursor |
| `y{n}w`         | Yank {n} words from the cursor |
| `yiw`           | Yank the word |
| `yi<' ">`       | Yank inside of the <' "> |
| `yi<( { [>`      | Yank inside of the <( { [> |
| `ye`            | Yank to the end of the word from the cursor |
| `y0`            | Yank to the beginning of the line from the cursor |
| `y$`            | Yank to the end of the line from the cursor |
| `y%`            | Yank the whole block of parentheses |
| `yt{char}`      | Yank up until the next {char} |
| `yT{char}`      | Yank up until the previous {char} |

---

## Pasting

| Command | Description |
|---------|-------------|
| `p`     | Paste after the cursor / below the current line |
| `P`     | Paste before the cursor / above the current line |

---

## Indentation

| Command  | Description |
|----------|-------------|
| `>>`     | Indent selection to the right |
| `<<`     | Indent selection to the left |
| `==`     | Auto-indent selection |
| `gg=G`   | Auto-indent the whole file |

---

## Search

| Command       | Description |
|---------------|-------------|
| `/{query}`    | Search forwards for {query} |
| `?{query}`    | Search backwards for {query} |
| `n`           | Go to the next occurrence of the search |
| `N`           | Go to the previous occurrence of the search |
| `*`           | Go to the next occurrence of the selected word |
| `#`           | Go to the previous occurrence of the selected word |

---

## Marking

| Command     | Description |
|-------------|-------------|
| `m{char}`   | Mark location and point to {char} |
| `'{char}`   | Go to the location of {char} |

---

## Search & Replace

| Command                       | Description |
|-------------------------------|-------------|
| `:%s/{old}/{new}/g`           | Replace {old} with {new} in the whole file |
| `:s/{old}/{new}/g`            | Replace {old} with {new} in the selection |

---

## Register

| Command       | Description |
|---------------|-------------|
| `:reg`        | Show all the registers |
| `"{reg}p`    | Paste the item stored in register {reg} |
| `"{reg}yy`   | Yank the line into register {reg} |
| `"+yy`       | Yank from Vim to OS clipboard |
| `"+p`        | Paste from OS clipboard to Vim |
| `"0p`        | Last yanked register |

---

## Macros

| Command     | Description |
|-------------|-------------|
| `q{reg}`    | Start recording macro to register {reg} |
| `q`         | Stop recording macro |
| `@{reg}`    | Run the saved macro from register {reg} |

---

