# Vim Commands

## Navigation

### Normalmode
<kbd> Ctrl + B </kbd> Previous Page  
<kbd> Ctrl + F </kbd> Next Page  
<kbd> '' </kbd> go to previous line  
<kbd> `` </kbd> go to previous cursor position  
<kbd> H </kbd>  move the cursor to the top row on the screen  
<kbd> M </kbd>  move the cursor to the middle row on the screen  
<kbd> L </kbd>  move the cursor to the last row on the screen  

### Visualmode
<kbd> af </kbd> expand selection paragraphwise 

## Deletion/Insertion
<kbd> I </kbd> insert to beginning of current line  
<kbd> A </kbd> append text to end of current line  
<kbd> D </kbd> delete to end of current line  
<kbd> dw </kbd> delete current word (starting from current cursor position)  
<kbd> dG </kbd> delete to bottom of file  
<kbd> d) </kbd> delete a sentence (sentences are delimited by TWO spaces)  
<kbd> d% </kbd> delete to the matching bracket, brace, or parenthesis  
<kbd> d” </kbd> delete to the last place we jumped from  
<kbd> dtp </kbd> delete through the letter p, but leaves the p  
<kbd> dfp </kbd> delete to and including the letter p  

## Edits
<kbd> sstring ESC </kbd> substitute the character under the cursor with string  
<kbd> cwstring ESC </kbd> change current word to string  
<kbd> c$string ESC </kbd> change from cursor to end of line with string  
<kbd> ccstring ESC </kbd> change current line to string  

## Substitution
