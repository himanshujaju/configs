## Legend

| Symbol | Key Name          |
|--------|-------------------|
| ⌘      | Command           |
| ⌥      | Option (Alt)      |
| ⌃      | Control           |
| ⇧      | Shift             |
| `      | Backtick (top-left, under Esc) |

---

## Modes

| Key         | Action                    |
|-------------|--------------------------|
| `i`         | Insert before cursor      |
| `v`         | Visual mode (select)      |
| `V`         | Visual line mode          |
| `<Esc>`     | Return to normal mode     |

## Movement

| Key         | Action                       |
|-------------|------------------------------|
| `h` `j` `k` `l` | Left, Down, Up, Right    |
| `w` / `b`   | Next/previous word           |
| `e`         | End of word                  |
| `$`         | Start/end of line            |
| `G`         | Top/bottom of file           |
| `%`         | Jump to matching bracket     |
| `f{char}`   | Find char on line            |

## Editing

| Key         | Action                           |
|-------------|---------------------------------|
| `x`         | Delete char under cursor        |
| `dd`        | Delete (cut) line               |
| `yy`        | Yank (copy) line                |
| `p` / `P`   | Paste after/before cursor       |
| `u`         | Undo                            |
| `^r`        | Redo                            |
| `.`         | Repeat last change              |

## Visual Mode

| Key         | Action                          |
|-------------|--------------------------------|
| `v`         | Start visual (char) select     |
| `V`         | Start visual line select       |
| `y`         | Yank (copy) selection          |
| `d`         | Delete selection               |
| `>` / `<`   | Indent/outdent selection       |

## Search & Replace

| Key             | Action                           |
|-----------------|---------------------------------|
| `/pattern`      | Search forward for pattern      |
| `?pattern`      | Search backward                 |
| `n` / `N`       | Next/previous match             |
| `:%s/foo/bar/g` | Replace all foo with bar        |

## VSCode Essentials (Normal Mode, macOS)

| Key                   | Action                        |
|-----------------------|------------------------------|
| `:w`                  | Save file                     |
| `:q`                  | Close file                    |
| `:wq`                 | Save and close                |
| `⌘P`                  | Quick file open               |
| `⌘⇧E`                 | Focus file explorer           |
| `⌘\`                  | Split editor                  |
| `⌘W`                  | Close editor                  |
| `⌃Tab`                | Next tab                      |
| `⌃⇧Tab`               | Previous tab                  |
| `⌘⇧F`                 | Find in files                 |
| `⌘⇧O`                 | Go to symbol in file          |
| `F12`                 | Go to definition              |
| `⌃-` / `⌃⇧-`          | Navigate back/forward         |

## Pane/Window Navigation

| Key         | Action                              |
|-------------|-------------------------------------|
| `⌃H`        | Focus left editor group             |
| `⌃L`        | Focus right editor group            |
| `⌃J`        | Focus editor group below            |
| `⌃K`        | Focus editor group above            |

## Terminal

| Key             | Action                              |
|-----------------|-------------------------------------|
| `` ⌃` ``        | Toggle terminal                     |

---

## Tips

- Use `:noh` to clear search highlighting.
- Use `:vsp filename` or `:sp filename` to split window with file.
- Use `:bnext`, `:bprev` to switch buffers (files).

