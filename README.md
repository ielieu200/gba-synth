# GBA Synth

init commmit - initializing environment

# Reference
https://gbadev.net/gbadoc/registers.html

# How to build

```
make
open *.gba
```

# Graphics
Graphics Mode: 0
REG_DISPCNT = 0;

# Audio
https://gbadev.net/gbadoc/audio/registers.html
## Channel 1
square wave with sweep

## Channel 2
square wave with duty cycle and env

## Channel 3
4 bit DAC that plays 4 bit samples 

## Channel 4
pseudo noise with envelope