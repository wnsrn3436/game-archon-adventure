# Archon's Adventure

A game where you play StarCraft's Archon and push forward through the bullet curtain of a Dragoon army. It has stages, boss fights and sound.

<p>
  <img src="docs/screenshots/screenshot-1.png" width="480" alt="Gameplay">
</p>


## How to play

Download from Releases and run it.

Move the Archon with the arrow keys and hold space to stop. Touching a Dragoon shot kills you. After the stage come three boss fights in a row.

The difficulty tests your patience, so on the death screen you can press 1 to 4 to jump to a section. 1 is the stage, 2 to 4 are the boss fights.


## How it works

The whole flow is five rooms: one stage, one death screen and three boss fights. The cheat keys are an object on the death screen with key events for 1 to 4, each attached to an action that goes to a different room. No progress is saved anywhere, room changes are all there is.


## Files

| Path | Contents |
|---|---|
| `source/archon-adventure.gmk` | Original project file |
| `source/split/` | Text tree produced by GmkSplitter |
| `docs/screenshots/` | Screenshots |
| Releases | Distributed build |


## License

CC BY-NC-ND 4.0. Unmodified copies may be shared for noncommercial purposes with attribution. Modified versions and commercial use are not allowed. Bundled libraries, graphics, sounds, and maps made by other people keep their own rights. See [LICENSE](LICENSE).
