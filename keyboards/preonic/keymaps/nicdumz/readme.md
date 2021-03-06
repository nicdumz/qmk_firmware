# nicdumz's Preonic keymap

This keymap is primarily based on smt's preonic keymap, which in turn is derived
from the default Preonic keymap, which in turn is derived from Planck's default.

## Qwerty

http://www.keyboard-layout-editor.com/#/gists/a99c883e29e2a0635eaee8501599540b

```
 ,-----------------------------------------------------------------------------------.
 |   `  |   1  |   2  |   3  |   4  |   5  |   6  |   7  |   8  |   9  |   0  | Bksp |
 |------+------+------+------+------+------+------+------+------+------+------+------|
 | Tab  |   Q  |   W  |   E  |   R  |   T  |   Y  |   U  |   I  |   O  |   P  | Bksp |
 |------+------+------+------+------+-------------+------+------+------+------+------|
 | Esc  |   A  |   S  |   D  |   F  |   G  |   H  |   J  |   K  |   L  |   ;  |  "   |
 |------+------+------+------+------+------|------+------+------+------+------+------|
 | Shift|   Z  |   X  |   C  |   V  |   B  |   N  |   M  |   ,  |   .  |   /  |Enter |
 |------+------+------+------+------+------+------+------+------+------+------+------|
 | Ctrl | Ctrl | Alt  | GUI  |Lower |Space |Space |Raise | Left |  Up  | Down |Right |
 `-----------------------------------------------------------------------------------'
```

## Lower

http://www.keyboard-layout-editor.com/#/gists/0c8e059fd66c1d2ab54665a4b823c1cc

```
 ,-----------------------------------------------------------------------------------.
 |   `  |   1  |   2  |   3  |   4  |   5  |   6  |   7  |   8  |   9  |   0  | Del  |
 |------+------+------+------+------+------+------+------+------+------+------+------|
 |   0  |   1  |   2  |   3  |   4  |   5  |   6  |   7  |   8  |   9  |   0  | Del  |
 |------+------+------+------+------+-------------+------+------+------+------+------|
 |   $  |  F1  |  F2  |  F3  |  F4  |  F5  |  F6  |   _  |      |      |      |      |
 |------+------+------+------+------+------|------+------+------+------+------+------|
 |      |  F7  |  F8  |  F9  |  F10 |  F11 |  F12 |      |      |      |      |      |
 |------+------+------+------+------+------+------+------+------+------+------+------|
 |      |      |      |      |      |             |      | Home |PageUp|PageDn| End  |
 `-----------------------------------------------------------------------------------'
```

## Raise

http://www.keyboard-layout-editor.com/#/gists/e881241cdc2d10efaa26a515700f87ca

As a developer, it makes the most sense for me to group all the commonly-used
symbols that don't fit on the main layer. In particular, having the dual-column
of parens-braces-brackets really helps a lot. I've also added cursorkeys to
correspond to the arrows.

I haven't completely filled this layer, which leaves room for future mappings
and macros.

```
 ,-----------------------------------------------------------------------------------.
 |   ~  |   !  |   @  |   #  |   $  |   %  |   ^  |   &  |   *  |   (  |   )  | Del  |
 |------+------+------+------+------+-------------+------+------+------+------+------|
 |   ~  |   !  |   @  |   #  |   $  |   %  |   ^  |   &  |   *  |   {  |   }  | Del  |
 |------+------+------+------+------+-------------+------+------+------+------+------|
 |      |      |      |      |      |      |   _  |   -  |   +  |   [  |   ]  |  |   |
 |------+------+------+------+------+------|------+------+------+------+------+------|
 |      |      |      |      |      |      |   -  |   /  |   =  |   [  |   ]  |  \   |
 |------+------+------+------+------+------+------+------+------+------+------+------|
 |      |      |      |      |      |             |      | Next | Vol+ | Vol- | Play |
 `-----------------------------------------------------------------------------------'
```

## Adjust (Lower + Raise)

Utility layer. This is where I'd switch between Qwerty and Dvorak, ~~fool around
with~~ adjust the audio/music settings, or put the Preonic into bootloader mode.

```
 ,-----------------------------------------------------------------------------------.
 |  F1  |  F2  |  F3  |  F4  |  F5  |  F6  |  F7  |  F8  |  F9  |  F10 |  F11 |  F12 |
 |------+------+------+------+------+------+------+------+------+------+------+------|
 |      | Reset|      |      |      |      |      |      |      |      |      | Reset|
 |------+------+------+------+------+-------------+------+------+------+------+------|
 |      |      |      |Aud on|AudOff|AGnorm|AGswap|      |      |      |      |      |
 |------+------+------+------+------+------|------+------+------+------+------+------|
 |      |Voice-|Voice+|Mus on|MusOff|MidiOn|MidOff|      |      |      |      |      |
 |------+------+------+------+------+------+------+------+------+------+------+------|
 |      |      |      |      |      |             |      |      |      |      |      |
 `-----------------------------------------------------------------------------------'
```
