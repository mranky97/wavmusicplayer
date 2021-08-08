# wavmusicplayer
This repository is for a LPC1768 based WAV music player

The wav player uses SD card to play songs from. FatFS is used to accomplish this. The UI is implemented on an OLED display which displays all the wav files in the SD card.
Four buttons are mapped to hardware interrupt for various functions like play/pause forward backward.
