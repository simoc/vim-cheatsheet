# vim-cheatsheet
Vim commands that I frequently forget.

## Split Windows

`:vsplit` splits window vertically

`:split` splits window horizontally

`CTRL w h`, `CTRL w j`, `CTRL w k`, `CTRL w l` moves left, down, up or right
to next split window

## Global Actions

`:g/foo/d` deletes all lines that contain `foo`
`:g!/foo/d` deletes all lines that do not contain `foo`

