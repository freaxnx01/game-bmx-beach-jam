# BMX Beach Jam 🚲

**▶ Play it:** https://github.freaxnx01.ch/game-bmx-beach-jam/

A retro 8-bit BMX game inspired by the classic *California Games* BMX event. Pedal down a sunny California beach course, launch off kickers, and pull aerial tricks for points before the 60-second timer runs out.

**Play it:** open `index.html` in any modern browser — no build step, no dependencies (one Google Font loaded from CDN; the game still works offline with a fallback font).

## Controls

| Key | Action |
|---|---|
| → | Pedal / accelerate |
| ← | Brake (on ground) |
| Space | Bunny hop |
| ← / → (in air) | Backflip / frontflip |
| ↑ (in air) | 360 spin |
| ↓ (hold in air) | Tabletop |

Land level with the slope or you wipe out and lose pending trick points. Trick points bank on clean landings. Finish the course for a time bonus. Best score is saved locally.

## Tech

- Single-file HTML5 canvas game, 320×180 internal resolution upscaled with pixelated rendering
- No frameworks, no assets — all graphics drawn procedurally per frame
- Web Audio API chiptune sound effects
- Seeded RNG course generation (same course every run)

## License

MIT