# vim-commands

Going to the start of the file: gg
<br />
Going to the end of the file: G (shift g)
<br />
Going to a specific line: <lineNumber>gg (20gg -> goes to line 20)

Deleting one line: dd

Going to visual mode: v
<br />
Going to visual line mode: V (shift + v)

Moving between two paranthesis: % (shift + 5)

select everything within paranthesis: v%

Delete till a specific word: d/(the text)(enter)

Shift + 8 (*): Search forward for the current word under the cursor.
<br />
Shift + 3 (#): Search backward for the current word under the cursor.


Deleting all the content of a file: ggdG
<br />
Selecting all the content of a file: ggvG

Go to a new line and start typing in insert mode: o

```a```: Enter insert mode <strong>after</strong> cursor's current position
<br />
```A```: Enter insert mode <strong>at the end of the current line</strong>.

```dw```: Deletes the word under the cursor, up to the first space or punctuation
<br />
```diw```: Deletes (cut) the whole word under the cursor
<br />


```viw```: Select the word under the cursor
<br />
```vii```: ...

Really good command for not using the mouse to see the content of a file: <br />
```H``` - move to top of screen
<br />
```M``` - move to middle of screen
<br />
```L``` - move to bottom of screen


Really cool combo  commands (last one is my favorite): <br />
```vi{```: Select everything inside {} (without the braces).
<br />
```vi(```: Select everything inside () (without the parentheses).
<br />
```va{```: Select everything inside {} (including the braces).
<br />
```va(```: Select everything inside () (including the parentheses).
<br />
```vi{dbo```: Select everything inside {}, delete it, go to the previous word, and open a new line to type.
<br />

My way to memorize it: <br />
```vi{``` -> select (v) inside (i) the brace ( { )
<br />
```va{``` -> select (v) all (a) and the brace ( { )
<br />

```S``` -> clear current line then go to insert mode
<br />
```D``` -> delete to end of line
<br />

Undo: u
<br />
Redo: (Ctrl)r

Going to the explorer bar: (Ctrl)0

