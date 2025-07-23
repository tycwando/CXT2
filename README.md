# CXT2 CHANGELOG

### Version [1.0.0] | [7-21-2025]

## General 
- Updated client sided state machine to be more responsive to the client.
- Entirely recoded the movement in contrast to the prior update.

 ## Bug Fixes
- Aerial movement no longer is as clunky as it was before. 
- Momentum properly works and can conserve any move in the game, instead of it being as awkward as it was before.
- DeltaTime no longer fucks up the entire movement system, now reliably has the same outcome at any fps.

## Additions | Reworks
- Rescripted A-ni-ki
- Added a 4 frame jump squat and 4 frame landing to every character. (As of Version 1.0.0)
- You can now lock onto the target by pressing V and hovering your mouse over the target. This can be disabled by pressing it a second time.
- Whilst locked on, you now have access to a different variety of normals, I hope you enjoy this change.
- Jump heights and dash lengths are now character specific.
- Updated a majority of the animations to instead be interpolated. People fear games that have soul it seems.
- Redid the entirety of the character's controller code.

## A-NI-KI Changes
- WWQ now properly has invulnurable frames from activation to the end of its duration. It is a wonderful reversal.
- DDSC now spawns an orb.

## Notes [7-14-2025]
The main problem I had with A-ni-ki was the fact that I couldn't properly express his characteristics whilst adding new mechanics in the game which entirely counteract how he should/would play with them. So, I decided to fully redo the character and make him more focused on how he would work with the game's mechanics as opposed to adding them in as an afterthought to his pre-existing kit.

## Notes [7-21-2025]
With the addition of character specific movement, I've also been contemplating on removing dashes for certain characters and giving them different movement options. I'll think more about that later on.
