# The Lavender Room

A pixel-art DJ simulation set in a cozy queer dive bar. You're on the decks from 9 PM to 4 AM, and the mixer is the only control you have over the crowd.

**[Play it in your browser →](https://YOUR-USERNAME.github.io/the-lavender-room/)**

![The mixer in action: tempo, bass, highs, reverb, a filter build and drop, then drive and volume](media/mixer-demo.gif)

## How to play

1. **Pick tonight's track.** Upload a song (MP3, WAV, M4A), load a MIDI file, or use one of the three built-in house tracks.
2. **Choose how it plays.** Use the original recording, or let the game transcribe it into a synth version, with melody, chords, bass and drums written out as MIDI notes, all inside the browser. You can preview both and save the MIDI file.
3. **Work the mixer.** Tempo, bass, mids, highs, filter, reverb, drive and volume all change the sound and the crowd.
4. **Read the room.** Hover over (or tap) anyone to see whether they're dancing, drinking and having a good time, and what they're thinking. The black tick on the energy meter is what the crowd wants at this hour.
5. **Survive until 4 AM.** Every guest leaves a review on the way out. The night's star rating is the average of those reviews, and the next night's crowd depends on how word gets around.

## How the crowd works

- Every patron has their own taste in tempo, bass, brightness and energy, and what the room wants shifts through the night: a gentle warm-up, a high-energy peak, then a wind-down.
- Leaving the mix untouched gets boring; yanking the faders around jars people. Hold the filter low for a few seconds, then throw it open, for a drop.
- Happy patrons dance, stay longer, drink more, tip, buy rounds and text their friends to come down. Unhappy ones nurse a drink and leave early.
- Rarer events depend on the music too: bathroom hookups (slower, bassier, more reverb), and fights (harsh, fast, loud, distorted music plus drunk, unhappy people). Fights cost money in damage, and security throws both people out.

## About the transcription

The synth version is produced entirely in your browser with signal processing: beat tracking, harmonic/percussive separation, tuning detection, pitch tracking, chord estimation and drum detection. It works best on songs with a clear lead melody and a steady beat. Busy mixes and heavily processed vocals will come out rougher; try the octave buttons if the melody lands in the wrong register.

## Running it yourself

It's a single self-contained file, `index.html`. Open it in a browser, or host the folder anywhere that serves static files. It loads two Google Fonts and nothing else; no build step and no server code.

## Credits

Made by Jupiter ([jupiterbhanot.com](https://jupiterbhanot.com)).
