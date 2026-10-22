was made for jetbrainsmono size 11 idk if itll work with other fonts
also idk if u can run it on other terminal emulators beside kitty 


1. kitten icat --z-index=-1 --place 66x14@0x0 --transfer-mode=file ~/fetch/image.png

2. fastfetch --logo none | sed 's/^/                              /' 

 the 's/^/                              /' part is the spacing so the actual fastfetch displays the info in the frame 

sorry that u have to run two commands instead of one but yh i dont use this anymore n idk how would i fix that anyway

alias f='kitten icat --z-index=-1 --place 66x14@0x0 --transfer-mode=file ~/Pictures/fetchimage.png'
alias ff='fastfetch --logo none --pipe false | sed "s/^/                              /"'

its ass but i was new at the time yk?
