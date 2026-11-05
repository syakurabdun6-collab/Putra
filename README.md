# Hellfire Gas — Fabric 26.1.2

## Prototype features
- Right-click the Hellfire Gas Fruit to activate a 45-second transformation.
- Applies Fire Resistance, Speed, and Absorption.
- Spawns a three-layer flame burst on activation.
- While Fire Resistance is active, three orbiting flame points and rising embers follow the player.
- Fruit cooldown: 12 seconds.

**Prototype note:** Fire Resistance is used as the synchronized visual-state marker in this first version. As a result, ordinary Fire Resistance from another source also activates the aura. A later version can replace this with a dedicated transformation state.

## Build
Use Java 25 and the Gradle versions in `gradle.properties`:
```sh
gradle build
```
The mod JAR is created in `build/libs/`.
