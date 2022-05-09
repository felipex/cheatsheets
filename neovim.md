---
Vim/NeoVim Cheetsheet
---

### Navigation/Cursor Movement


```
 k
h l
 j
```

`h` -> move cursor left  
`l` -> move cursor right  
`k` -> move cursor up  
`j` -> move cursor down  
***
`0` -> jump to the start of the line

`$` -> jump to the end of the line

`gg` -> jump to the start of the document

`G` -> jump to the end of the document

---
Seach and Replace
---
`:%/foo/bar/g` -> search and replace (https://linuxize.com/post/vim-find-replace/)

---
Windows Navigation
---
* `Ctrl + ws ` - split window horizontaly
* `:split filename` - split window horizontaly
* `:vsplit filename` - split window verticaly
* `:bn` - next window
* `:bp` - previous window
* `:bd` - close window
* `:only` - keep only this window open
* `:ls` - show current buffers
* `:b #n` - open buffer n in this window
* `:hide` - hide current window

---
Configuration
---
|---------|-------|
| Command | Description|
|---------|-------|
| `:set number` | show line numbers
| `:set nonumber` | hide line numbers
| `:set tabstop=4` | set tabs
| `:set shiftwidth=4` | indenting is 4 spaces

Referências

https://vim.rtorr.com/

https://github.com/mattmc3/neovim-cheatsheet

https://devhints.io/vim

https://github-wiki-see.page/m/yqlbu/neovim-server/wiki/Cheat-Sheet

https://www.cs.swarthmore.edu/oldhelp/vim/

(MARKDOWN) - https://www.markdownguide.org/basic-syntax

