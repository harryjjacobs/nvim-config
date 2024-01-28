# nvim-config
my neovim config

## cheatsheat

`<leader>` is space

`:Telescope keymaps` is probably the most useful command as it's easily searchable.

`<leader ch` for cheatsheat

https://github.com/nvim-telescope/telescope.nvim

### Language Server Protocol (LSP) stuff

| description | mode | keys | 
| --- | --- | --- |--- |
| LSP declaration | n | g D |
| LSP definition  | n | g d |
| LSP references  | n | g r |

`<leader> c a` for "code action" (i.e. apply a quick fix)
`<leader> f` to open the diagnostics window for the current line

### find/replace

find a file: `<leader> ff`

`:vimgrep`

`:Telescope live_grep` for live search in current folder

`:%s/search/substitute/` for find and replace in the current buffer

### file browsing

`ctrl-n` to toggle the file explorer tab

`<leader> e` focuses the file explorer if it's open


### misc

open a terminal: `:te`

