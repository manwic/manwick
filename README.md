# Manwick

A 2D top-down tactical team shooter built with LibGDX, featuring 4v4 combat, skill-based shooting mechanics, and strategic depth.

## Project Overview

**Genre**: 2D Top-Down Tactical Shooter  
**Platform**: PC (Windows/Mac/Linux)  
**Engine**: LibGDX (Java)  
**Target**: 4v4 multiplayer with offline single-player support  
**Match Duration**: 5-7 minutes per match  

## Key Features

- **Tactical Combat**: Skill-based shooting with crosshairs and recoil patterns
- **Team-Based**: 4v4 multiplayer matches with team coordination
- **Multiple Health System**: 150 HP base with armor and healing systems
- **Defensive Mechanics**: Cover system, dodge rolling, crouching, and leaning
- **Mixed Combat**: Ranged weapons, melee weapons, and hand-to-hand combat
- **5 Game Modes**: Team Deathmatch, Capture and Hold, Search and Destroy, King of the Hill, Escort Mission
- **3 Maps**: Factory Floor, Urban Streets, Military Base

## Weapon Arsenal

### Primary Weapons
- **Assault Rifles**: AK-47 style (35 dmg, 600 RPM), M4 style (30 dmg, 750 RPM)
- **SMG**: MP5 style (25 dmg, 900 RPM)
- **Shotgun**: Pump action (120 dmg close range, 60 RPM)
- **Sniper**: Bolt action (120 dmg, 40 RPM, 2x scope)
- **Pistol**: Standard sidearm (40 dmg, 300 RPM)

### Melee Weapons
- **Hand-to-Hand**: Punch (25 dmg), Kick (35 dmg), Grapple (40 dmg + stun)
- **Melee Weapons**: Knife (60 dmg), Baseball Bat (80 dmg), Sword (90 dmg)

### Equipment
- **Grenades**: Frag, Flashbang, Smoke
- **Healing**: Med Kits (50 HP restoration)
- **Armor**: Light (+25 HP), Heavy (+50 HP)

## Development Status

### Phase 1: Foundation [COMPLETE]
- ✅ Project structure and architecture
- ✅ LibGDX setup and configuration  
- ✅ Basic character movement system
- ✅ Team identification system
- ✅ Development environment ready

### Phase 2: Combat Core [IN PROGRESS]
- 🔄 Combat system foundation
- 🔄 Weapon system implementation
- 🔄 Health and damage systems
- 🔄 Defensive mechanics
- 🔄 Melee combat system

### Upcoming Phases
- **Phase 3**: Maps & Environment
- **Phase 4**: Game Modes  
- **Phase 5**: Multiplayer & Networking
- **Phase 6**: Polish & Systems

## Technical Specifications

### System Requirements
**Minimum**:
- OS: Windows 10, macOS 10.15, Ubuntu 18.04
- Processor: Intel i3-6100 / AMD FX-6300
- Memory: 4 GB RAM
- Graphics: GTX 750 Ti / RX 560
- Storage: 2 GB available space

**Recommended**:
- OS: Windows 11, macOS 12, Ubuntu 20.04
- Processor: Intel i5-8400 / AMD Ryzen 5 2600
- Memory: 8 GB RAM
- Graphics: GTX 1060 / RX 580
- Storage: 4 GB available space

### Performance Targets
- **Frame Rate**: 60+ FPS stable
- **Network Latency**: <100ms optimal
- **Load Times**: <5 seconds map loading
- **Players**: 8 players per match maximum

## Project Structure

```
TacticalShooter/
├── Assets/           # Game assets (characters, weapons, maps, UI)
├── Scripts/          # All source code organized by system
├── Scenes/           # Game scenes (menus, game modes, maps)
├── Documentation/    # Complete project documentation
├── Audio/            # Sound effects, music, voice
├── Textures/         # Visual assets organized by type
├── Tools/            # Development tools and utilities
└── Build/            # Build output directory
```

## Documentation

- **[Master Task List](Documentation/MASTER_TASK_LIST.md)** - Complete development roadmap
- **[Getting Started](Documentation/GETTING_STARTED.md)** - Development setup guide
- **[Project Structure](Documentation/PROJECT_STRUCTURE.md)** - Detailed folder organization
- **[Code Reference](Documentation/CODE_REFERENCE.md)** - File structure and code purposes

### Phase Documentation
- [Phase 1: Foundation](Documentation/TaskLists/PHASE_1_FOUNDATION.md) [COMPLETE]
- [Phase 2: Combat Core](Documentation/TaskLists/PHASE_2_COMBAT.md) [ACTIVE]
- [Phase 3: Maps & Environment](Documentation/TaskLists/PHASE_3_MAPS.md) [READY]
- [Phase 4: Game Modes](Documentation/TaskLists/PHASE_4_GAMEMODES.md) [READY]
- [Phase 5: Multiplayer](Documentation/TaskLists/PHASE_5_MULTIPLAYER.md) [READY]
- [Phase 6: Polish & Systems](Documentation/TaskLists/PHASE_6_POLISH.md) [READY]

## Getting Started

### Prerequisites
- Java JDK 21 or higher
- IntelliJ IDEA or Eclipse IDE
- LibGDX framework
- Git for version control

### Setup Instructions
1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/tactical-team-shooter.git
   cd tactical-team-shooter
   ```

2. Import project into your IDE
   - IntelliJ: File → Open → Select project directory
   - Eclipse: Import → Existing Projects into Workspace

3. Configure LibGDX
   - Ensure all dependencies are resolved
   - Set up run configurations for desktop launcher

4. Start Development
   - Review [Getting Started Guide](Documentation/GETTING_STARTED.md)
   - Begin with Phase 2 tasks in [Combat Core](Documentation/TaskLists/PHASE_2_COMBAT.md)

## Development Roadmap

The project is organized into 6 phases with detailed task breakdowns:

1. **Foundation** - Core systems and architecture [COMPLETE]
2. **Combat Core** - Weapons, health, combat mechanics [IN PROGRESS]  
3. **Maps & Environment** - 3 maps with environmental systems
4. **Game Modes** - 5 distinct game modes implementation
5. **Multiplayer** - Networking, matchmaking, server systems
6. **Polish & Systems** - UI, audio, progression, AI

**Total Development**: 200+ organized tasks across all phases

## Contributing

This is currently a solo development project. Future collaboration guidelines will be established as the project progresses.

## License

[License to be determined]

## Contact

[Contact information to be added]

---

**Current Status**: Foundation Complete, Combat Development in Progress  
**Next Milestone**: Complete weapon system implementation  
**Last Updated**: Current