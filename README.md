# ChordLens

A glassmorphism-inspired, single-page practice companion. Upload an MP3 locally, choose guitar/piano/ukulele, transpose the demo chord sheet, and follow line highlights as the song plays.

## Run it

No install or build step is needed. Open `index.html` in a browser, or use the VS Code Live Server extension for a local server.

## Current MVP scope

- MP3 file upload and browser-native playback (audio never leaves the device)
- Demo lyrics and chord progression with automatic playback highlighting
- Guitar, ukulele, and piano chord-shape displays
- Semitone transposition
- Responsive UI and keyboard play/pause shortcut (`Space`)

## Intentional limitation

This MVP does not claim to transcribe arbitrary songs. Automated chord recognition, lyrics extraction, and lyric/chord alignment are separate advanced features. Keeping the song sheet as editable demo data makes the product prototype reliable and legally safer for public demos.

## Suggested next steps

1. Let users edit and save their own lyrics/chords.
2. Support timestamped `.lrc` lyric files.
3. Add an audio-analysis backend for chord estimates, with user correction.
4. Add per-instrument chord voicing libraries.

