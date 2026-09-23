# Sanket Shikho

A sign language learning web app. Pick American Sign Language (ASL) or Indian Sign Language (ISL, coming soon), with instructions in English or Hindi.

## What's in version 1
- ASL alphabet A–Z (J and Z animated with a motion path)
- ASL numbers 0–10
- 12 everyday ASL words, animated on a signer figure
- 10-question quiz mixing all units
- English / हिंदी toggle, slow motion, left-handed (mirrored) view
- Progress saved on the device

## How it works
Everything is in `index.html`. Hand shapes are drawn with SVG from finger and thumb settings in the `SH` table, and animations move between keyframes. No build step is needed.

## Accuracy note
The drawings are simplified. Every sign should be checked by a Deaf signer or a certified interpreter before public release.
