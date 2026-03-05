## 🏔️ EverWrestle

[![Engine](https://img.shields.io/badge/Engine-Unreal%20Engine-478cbf)](https://www.unrealengine.com/de)
[![Role](https://img.shields.io/badge/Role-Lead%20Game%20Engineer_&_CoProducer-blue)](https://www.jannikkluge.com/#/about)
[![Language](https://img.shields.io/badge/Language-C++_&_BP-355570)](https://cplusplus.com)
[![Project](https://img.shields.io/badge/Project-Playable%20on%20itch.io-orange)](https://s4g.itch.io/everwrestle)

<img width="1920" height="1080" alt="EverWrestle_Banner" src="https://github.com/user-attachments/assets/9a53c2d8-e3b2-4647-97e5-0520591cc713" />

**EverWrestle** is a physics-based multiplayer party game centered around chaotic climbing and player-driven sabotage.  
Developed within a **10-week production timeframe** as part of the *School4Games* program, the project focuses on readable multiplayer physics, responsive interaction systems, and scalable gameplay design under real production constraints.

🔗 **Project page:** https://www.jannikkluge.com/#/projects/EverWrestle  
🌐 **Portfolio:** https://www.jannikkluge.com
 
---

## About the Game

In *EverWrestle*, two to four players compete to reach the top of a dangerous vertical mountain filled with obstacles, hazards, and cooperative challenges.  
Progress is only possible through a mix of **timing, and tactical player interaction**.

Key features:
- Physics-based multiplayer climbing gameplay  
- 2–4 player online party experience  
- Player interaction: punching, grabbing, lifting, and throwing  
- Ragdoll reactions triggered by hits, falls, and hazards  
- Vertical level progression with checkpoints and death zones  
- Round-based scoring system rewarding progress and sabotage

---

## My Role

I worked as **Lead Game Engineer** and **Co Producer** in a team of 8 people, contributing across gameplay systems, UI, performance optimization, and production pipelines.

### Core Responsibilities
- Implemented the [core gameplay loop](https://github.com/prayyOnIntelliJ/EverWrestle/blob/main/Source/EverWrestle/EverWrestleGameMode.cpp), structuring the full match flow from **Lobby → Map → Point Distribution → Next Round → Final Victory**
- Developed [Moving Objects](https://github.com/prayyOnIntelliJ/EverWrestle/blob/main/Source/EverWrestle/EverWrestleMovingObject.cpp), as well as multiple **environment hazards**, including the [Bear Trap](https://github.com/prayyOnIntelliJ/EverWrestle/blob/main/Source/EverWrestle/EverWrestleBearTrap.cpp), [Crush Trap and Spear Trap](https://github.com/prayyOnIntelliJ/EverWrestle/blob/main/Source/EverWrestle/EverWrestleMovingTrap.cpp), integrating them into the physics-based gameplay
- Designed and implemented the **complete UI system**, including multiplayer lobby interfaces such as [Create Lobby](https://blueprintue.com/blueprint/8dtppar4/), [Find Lobby](https://blueprintue.com/blueprint/0alxkxji/), and **Join Lobby**
- Built a [custom session subsystem](https://github.com/prayyOnIntelliJ/EverWrestle/blob/main/Source/EverWrestle/AdvancedSessionSubsystem.cpp) providing helper functionality for multiplayer features like **Create Session**, **Find Sessions**, and session management

---

## Teamwork, Time Pressure & Technical Growth

This project marked my **first experience developing a multiplayer physics game under strict production constraints** while collaborating closely with another developer.  
Within the 10-week timeframe, clear task separation, constant communication, and shared ownership of core systems were essential to delivering a stable and playable build.

A major technical challenge was maintaining **consistent and predictable physics behavior in a multiplayer environment**.  
Working with Chaos Physics and network replication required extensive debugging and experimentation to ensure interactions like grabbing, throwing, and ragdoll reactions remained responsive and fair for all players.

The project reinforced an important lesson: **systems must be designed with constraints in mind from the start**.  
Networking, physics determinism, and gameplay readability influenced many architectural decisions, shaping how mechanics, abilities, and player interactions were implemented.

---

## Tools & Technologies

- **Unreal Engine 5.6.1** – Core engine and scene system  
- **C++** – Gameplay logic and systems  
- **Blueprint** - UI  
- **Perforce** – Version control and collaboration  

More tools and engines I work with:  
➡️ https://www.jannikkluge.com/#/tools-and-engines

---

## Play the Game

You can find more information, downloads, and the itch.io demo here:  
➡️ https://s4g.itch.io/everwrestle

---

## Contact

🌐 Portfolio: https://www.jannikkluge.com  
📧 Email: *contact@jannikkluge.com*  
💼 GitHub: https://github.com/prayyOnIntelliJ
