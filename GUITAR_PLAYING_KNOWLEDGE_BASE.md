# Electric Guitar Performance Knowledge Base

## Instrument model
- Standard tuning, string 6 to 1: E2 A2 D3 G3 B3 E4.
- Internal MIDI open strings: 40, 45, 50, 55, 59, 64.
- Working fret range: 0-24.
- The same pitch can exist on several strings; fingering is chosen by minimizing fret jumps, string jumps, and extreme high-fret positions.

## Core articulations
- Hammer-on: the first note is picked, the next higher note is sounded by the fretting hand on the same string; use for small ascending intervals.
- Pull-off: the first note is picked, the next lower note is produced on the same string; use for small descending intervals.
- Slide: connect two notes on the same string with a continuous pitch transition; most useful when the fret distance is larger than a normal hammer/pull movement.
- Bend: raise the pitch continuously, commonly toward a nearby target; sustained bends can finish with vibrato.
- Vibrato: apply after a note has settled, especially at phrase endings rather than on every short note.
- Palm mute: short decay and reduced brightness; mainly rhythmic.
- Alternate picking: alternate down/up strokes in fast scalar runs; keep small velocity/timbre differences between directions.
- Tremolo picking: rapidly retrigger one pitch with alternating strokes.
- Sweep picking: move one picking direction across adjacent strings, usually for arpeggio-like shapes; notes should be close but not exactly simultaneous.
- Tapping: a fretting/tapping-hand attack; useful for wide intervals and fast legato figures.
- Pinch harmonic: emphasize a high harmonic on an accented lead note.

## Automatic performance rules used in V2.11
1. Assign a playable string/fret to each note before choosing technique.
2. Same string + small ascending interval -> hammer-on.
3. Same string + small descending interval -> pull-off.
4. Same string + wider connected interval -> slide.
5. Fast monophonic run -> alternate picking unless legato rules take precedence.
6. Monotonic movement across several strings -> sweep candidate.
7. Wide fast leap in Shred mode -> tapping candidate.
8. Long high phrase ending -> vibrato or pinch harmonic.
9. Long note followed by a 1-2 semitone target on the same string -> bend candidate.
10. No more than six principal simultaneous voices per guitar.

## Sources studied
- Fender: How to Solo on Guitar — alternate picking, bending, palm muting.
- Fender: Master Hammer-Ons and Pull-Offs.
- Berklee Online: Guitar Techniques — Hammer-ons, Pull-offs, and Slides.
- D'Hooge, Bigo, Degueernel (2023): Modeling Bends in Popular Music Guitar Tablatures.
- TART (2025): technique-aware guitar transcription separates pitch, expressive technique, string/fret assignment and tablature generation.
