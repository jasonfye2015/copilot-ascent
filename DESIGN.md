# Copilot Ascent

A retro roguelike metroidvania HTML5 game built from the ground up.

## Game Overview

The player climbs a massive tower, floor by floor, defeating bosses, gathering resources, and trying to lift a curse that has haunted their family for generations. Each death does not end the lineage forever: the next descendant continues the climb, carrying forward some traits and knowledge while the rest of the run resets.

## Core Pillars

### 1. The Tower
- The tower is vertical and massive.
- Each floor is a distinct, procedurally generated chamber complex.
- Floors contain rooms, minibosses, traps, loot, and a final boss gate.
- The player can return to the town at any time between floors or after death.

### 2. The Hub Town
- The town is a base of operations.
- Players can heal, purchase upgrades, manage gear, and review lineage progress.
- Town progression should feel meaningful but not overpowering.

### 3. The Hereditary Curse
- Failure is not total loss.
- The family lineage carries some persistent traits forward.
- Some upgrades remain, while most gear and run-specific rewards reset.

### 4. Replayability
- Procedural generation keeps each run distinct.
- Progression choices matter and help future runs feel different.
- Bosses and floor themes create a strong sense of exploration.

## Structure

### Player Systems
- Health, stamina, attack power, defense, movement speed
- Equipment slots: weapon, armor, trinket
- Temporary run loot, relics, and passive buffs

### Room Generation
- Rooms are built as a small grid with connected corridors.
- Each room has a type: combat, treasure, shrine, trap, rest, boss, shop, and empty.
- Boss room unlocks the next floor.

### Combat
- Classic action combat, simple but satisfying.
- Light melee/ranged attacks and dodge movement.
- Minibosses and boss patterns add tension and rhythm.

### Town Progression
- Upgrade permanent family traits
- Improve weapon crafting or smithing
- Unlock deeper stat bonuses and town services

## Design Goals

- Single-file HTML5 implementation for portability
- No build steps or external dependencies
- Easy to run locally and release on itch.io
- Modular code structure even inside one file
- Clear “one more run” loop

## Future Expansion

- More enemy archetypes
- Inventory upgrades and crafting
- New floor biomes
- Mini-map improvements
- More town services and NPCs
- Local co-op or hot-seat multiplayer idea

## Long Term Vision

The game is intended to grow toward a deep roguelike metroidvania with long-term progression, multiple tower biomes, and a satisfying sense of the family curse being lifted over time.
