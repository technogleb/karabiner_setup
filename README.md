# karabiner_setup
Here are my karabiner(https://karabiner-elements.pqrs.org) setups, I use on my macbook.
One moves arrows **up,left,down,right** to **ijkl** keys, along with some other combinations.<br>
Other uses vim-like text navigation along with some other combinations <br>

## Installation
Install karabiner (https://karabiner-elements.pqrs.org) and launch <br>

Clone the repo and run  
`cp ./karabiner_vim.json ~/.config/karabiner/karabiner.json` for vim config  
and
`cp ./karabiner_ijkl.json ~/.config/karabiner/karabiner.json` for ijkl config  

## IJKL config
### Cursor navigation
* option + j ==> left_arrow
* option + l ==> right_arrow
* option + k ==> down_arrow
* option + i ==> up_arrow 

### Word navigation
* option + u ==> option + left_arrow
* option + o ==> option + right_arrow

### Sentence navigation
* option + h ==> command + left_arrow
* option + ; ==> command + right_arrow

### Spaces navigation
* left_control + l ==> left_control + right_arrow
* left control + j ==> left_control + left_arrow

`all options above also work with any additional modifier key provided, such as shift`


## VIM-like config
### Cursor navigation
* option + h ==> left_arrow
* option + l ==> right_arrow
* option + j ==> down_arrow
* option + k ==> up_arrow 

### Word navigation
* option + u ==> option + left_arrow
* option + o ==> option + right_arrow

### Sentence navigation
* option + g ==> command + left_arrow
* option + ; ==> command + right_arrow

### Spaces navigation
* left_control + l ==> left_control + right_arrow
* left control + h ==> left_control + left_arrow

`all options above also work with any additional modifier key provided, such as shift`
