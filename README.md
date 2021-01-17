# Piano-Scribe
Interactive online piano player with live transcription and midi playback.
Input is possible through midi input on Chrome, or computer keyboard and/or mouse on all browsers.

Play around with the latest version of it here https://ivan-v.github.io/Piano-Scribe/ ,
or see it as part of Virtual Bard: https://www.virtualbard.com/piano_scribe

![](screencapture.gif)

## Motivation
There's a clear gap of a browser-based input-to-sheet-music editor. This is my approach at making a simple in-browser keyboard which also transcribes the notes played. 

## Libraries Used
- Keith Horwood's audiosynth for live playback:
https://keithwhor.github.io/audiosynth/

- Verovio JS Toolkit for rendering input notes: 
https://github.com/rism-ch/verovio

- MIDI Player for playback of transcribed notes: 
https://github.com/rism-ch/midi-player


## Inspiration
- Anna Neovesky & Gabriel Reimers' pianoKeyboard, which transcribes using Verovio: 
https://github.com/annaneo/pianoKeyboard

## Future Work
- [ ] Sometime soon, I hope to make it simple to embed and create more comprehensive settings for it.
- [ ] Convert to Humdrum Verovio notaion https://verovio.humdrum.org/. This will require comprehensive rewriting, but would permit for multiple voices (chords that are made up of notes of different durations). An intuitive input method for this is not yet clear -- one option is to quantize live input through a virtual & interactive metronome.
- [ ] Add a selection of instruments for playback. This is possible in the WildWebMidi library, but will have to be implemented independently in both live playback (on input) and playback from sheet music (not on input). Perhaps there's a better way to do one method & library for both of those purposes.  

 
## Author

**Ivan Viro**
