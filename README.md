# My minimal emacs cheat sheet
---
This document is covered by the GNU General Public License (GNU GPL).
If you haven’t read the GPL before, please do so. It explains all the things that you are allowed to do with this documentation.

October 12 2015

:copyright: Alireza Pazhouhesh

[lidora.blog.ir](http://lidora.blog.ir)


---
Key bindings are expressed as follows:

<kbd>C-a</kbd> is <kbd>Ctrl</kbd> + <kbd>a</kbd>

<kbd>M-a</kbd> is <kbd>Meta</kbd> + <kbd>a</kbd>

---
### :left_right_arrow: BASIC CURSER CONTROL
|Keystrokes   			|Action          								|
| --------------------- | --------------------------------------------- |
| <kbd>C-f</kbd>       	| Move forward a character          			|
| <kbd>C-b</kbd>       	| Move backward a character         			|
| <kbd>M-f</kbd> 		| Move forward a word                          	|
| <kbd>M-b</kbd> 		| Move backward a word                          |
| <kbd>C-n</kbd>       	| Move to next line                 			|
| <kbd>C-p</kbd>       	| Move to previous line             			|
| <kbd>C-a</kbd>       	| Move to beginning of line         			|
| <kbd>C-e</kbd>       	| Move to end of line               			|
| <kbd>M-a</kbd>		| Move to beginning of sentence                 |
| <kbd>M-e</kbd> 		| Move to end of sentence                     	|
| <kbd>C-l</kbd>		| Find the cursor (1:Center, 2:Up, 3:Down)		|
| <kbd>M-g M-g</kbd> 	| Go to line 									|

---
### :heavy_check_mark: SELECT AND MARK
|Keystrokes 			|Action                   			|
| --------------------- | --------------------------------- |
| <kbd>C-SPC</kbd>  	| Select by line         			|
| <kbd>C-x SPC</kbd>  	| Select by column            		|
| <kbd>C-x C-x</kbd> 	| Go to other end of marked region 	|
| <kbd>M-h</kbd> 		| Mark paragraph 					|
| <kbd>C-x C-p</kbd> 	| Mark the current page 			|
| <kbd>C-x h</kbd> 		| Mark the whole buffer		  		|

---
### :x: INSERTING AND DELETING
|Keystrokes     		|Action                                         |
| --------------------- | --------------------------------------------- |
| <kbd>C-d</kbd>        | Delete one char forward  						|
| <kbd>M-d</kbd>        | Cut one word forward  						|
| <kbd>M-DEL</kbd>   	| Cut one word backward							|
| <kbd>C-k</kbd>        | Cut to the end of line						|
| <kbd>C-w</kbd> 		| Cut selected region 							|
| <kbd>M-w</kbd> 		| Copy selected region 							|
| <kbd>DEL</kbd>      	| Delete the character just before the cursor	|
| <kbd>C-y</kbd>        | Yanking (Paste)                     			|
| <kbd>M-y</kbd>    	| Choose what to paste from clipboard 			|
| <kbd>C-u 8 *</kbd>    | ********                                  	|
| <kbd>C-u 2 C-k</kbd>	| Kill two lines.                             	|

---
### :rewind: UNDO
|Keystrokes 		|Action	|
| ----------------- | ----- |
| <kbd>C-/</kbd>    | Undo  |
| <kbd>C-x u</kbd> 	| Undo 	|

---
### :open_file_folder: FILES
|Keystrokes 			|Action                 |
| --------------------- | --------------------- |
| <kbd>C-x C-f</kbd> 	| Open file             |
| <kbd>C-x C-s</kbd> 	| Save file             |
| <kbd>C-x C-w</kbd> 	| Save to file named as	|

---
### :page_facing_up: BUFFERS
|Keystrokes 			|Action                 |
| --------------------- | --------------------- |
| <kbd>C-x C-b</kbd> 	| List buffers        	|
| <kbd>C-x s</kbd>   	| Save some buffers   	|
| <kbd>C-x b</kbd>   	| Switch to a buffer  	|
| <kbd>C-x k</kbd>		| Kill a buffer			|

---
### :eyeglasses: SEARCHING
|Keystrokes			|Action            	|
| ----------------- | ----------------- |
| <kbd>C-s</kbd>    | Search forward 	|
| <kbd>C-r</kbd>    | Search backward	|

---
### :repeat: REPEATING
|Keystrokes 			|Action          	|
| --------------------- | ----------------- |
| <kbd>M-n</kbd> 		| Repeat n times	|
| <kbd>C-u</kbd> 		| Repeat 4 times 	|
| <kbd>C-u C-u</kbd> 	| Repeat 16 times	|

---
### :black_square_button: MANAGING WINDOWS
|Keystrokes     		|Action                            	|
| --------------------- | ---------------------------------	|
| <kbd>C-x 1</kbd>      | kill all but the current window	|
| <kbd>C-x 2</kbd>      | Split windows horizontally  		|
| <kbd>C-x 3</kbd>      | Split windows vertically          |
| <kbd>C-x 0</kbd> 		| Close the current window 			|
| <kbd>C-x ^</kbd> 		| Expand vertically 				|
| <kbd>C-x {</kbd> 		| Expand horizontally 				|
| <kbd>C-x 4 C-f</kbd>	| Find file in a new window         |
| <kbd>C-M-v</kbd>      | Scroll another window             |
| <kbd>C-X-o</kbd>      | Go to another other window   		|

---
### :white_check_mark: SPELL CHECKING
|Keystrokes        							|Action                         |
| ----------------------------------------- | ----------------------------- |
| <kbd>M-$</kbd> 							| ispell check a single word	|
| <kbd>M-x ispell-region</kbd> 				| check selected region			|
| <kbd>M-x ispell_buffer</kbd> 				| check current buffer 			|
| <kbd>M-x flyspell-mode</kbd> 				| use flyspell 					|
| <kbd>M-x ispell-change-dictionary</kbd>	| Set spelling dictionary 		|

---

### SHELL
|Keystrokes     		|Action                                						|
| --------------------- | --------------------------------------------------------- |
| <kbd>M-!</kbd> 		| Execute shell command 									|
| <kbd>C-u M-!</kbd> 	| Execute shell command and put output in current buffer 	|
| <kbd>M-x shell</kbd>	| Shell mode 												|

---
### :hash: SHELL MODE
|Keystrokes			 | Action              			|
| ------------------ | ---------------------------- |
| <kbd>C-c C-z</kbd> | Equal <kbd>C-z</kbd> command |
| <kbd>C-c C-d</kbd> | Equal <kbd>C-d</kbd> command |
| <kbd>C-c C-c</kbd> | Equal <kbd>C-c</kbd> command |

---
### :information_source: GETTING HELP
|Keystrokes 		|Action                   |
| ----------------- | ----------------------- |
| <kbd>C-h ?</kbd>  | Help suggestions        |
| <kbd>C-h c</kbd>  | Basic help              |
| <kbd>C-h f</kbd>  | Describe a function     |
| <kbd>C-h k</kbd>  | Describe a keystroke    |
| <kbd>C-h a</kbd>  | Command apropos         |
| <kbd>C-h i</kbd>  | Read included manuals   |
| <kbd>C-h r</kbd>  | The emacs editor help   |
| <kbd>q</kbd>      | Close Help buffer		  |
