# Sinking Feeling
A 2D, cooperative, horror puzzle platformer about descending into a massive sinkhole.

## About
Two players work together to reach the bottom of a sinkhole. The deeper they go, the darker and more unnerving things become. The only way forward is to solve puzzles with your partner, so you are forced to linger in uncomfortable places until you figure out how to move on.

**Design Pillars**: Cooperative. Unnerving. Cautious.

### Inspirations
- Little Nightmares
- Unravel Two
- Portal 2
- Sheepy: A Short Adventure

## Getting Started

### Requirements
- Unity Hub
- Unity Editor version: [`6000.3.9f1`](https://unity.com/releases/editor/whats-new/6000.3.9f1#installs)
- Git

### Setup
1. Clone the repository:
```sh
git clone git@github.com:nanokes/Sinking-Feeling.git
```
2. Open Unity Hub and choose "Add project from disk", then select the cloned folder.
3. Open the project with the Unity version listed above. Note: using another Unity version may break game code and version control
4. Open the main scene at `Assets/Scenes/MainScene` and press Play.

## Project Structure
```
Assets/
  Art/         Sprites, animations, tilesets
  Audio/       Music and sound effects
  Prefabs/     Reusable game objects
  Scenes/      Game scenes
  Scripts/     C# code
ProjectSettings/
Packages/
```

## Contributing
- Pull the latest `main` before starting work.
- Create a branch for each task: `feature/player-movement` or `fix/object-clipping-edge-cases` for example.
- Keep commits small following a clear SOC between them with clear messages.
- Open a pull request and get at least one teammate to review before merging into main.
- Try to avoid two people editing the same scene or prefab at once. Ask in Discord first, since Unity merge conflicts are painful.
- Link your pull request to its task on the task board.

Thanks for your help! :heart:
