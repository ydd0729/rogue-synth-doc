# Brick Fury: AI-Assisted Unity Game Development

## 1. Overview

This project is a **Unity-based Rogue-like game** in which players **move to avoid enemies** and survive waves of monsters. As players progress and **level up**, **cards appear** that provide **buffs and enhancements** to strengthen the player.  

The goal of this project is to explore how AI can **enhance and accelerate** the process of game development while preserving **human creativity and technical control**.  



---

## 2. Team Responsibilities

### Dong Yang
- Game planning and core gameplay design
- Main character model generation using *Hunyuan 3D v2.1*
- Card generation and integration within the game
- Player control and skill system implementation
- Game Over UI design and logic
- Background music and skill sound generation

### Renkai Ma
- Designing and generating **enemy models** using AI-assisted tools (*Hunyuan 3D v3.0*)
- Designing and implementing **enemy behavior logic** with the help of AI tools such as *ChatGPT*, accelerating development and improving system efficiency
- Developing and optimizing most of the **UI**, including the **Start Menu**, **Pause Screen**, and **in-game value display**
- Using generative AI tools to create and place **in-game objects** and environmental assets
- Arranging **terrain layouts** and object placement to improve level design, visual balance, and gameplay flow
- Generating enemy attack sound effects using *Stable Audio Open 1.0*

### Duoer Dai
- Card image generation using AI tools (*Q4 GGUF*)
- Initial design of the Start UI (main menu layout and structure)
- Generation of UI images and visual elements using AI-assisted design tools

---

## 3. Project Tools and Their Roles

### Renkai Ma
| Tool | Role | Example Usage |
|------|------|----------------|
| **Hunyuan 3D v3.0** | 3D model generation | Generated enemy models and environmental objects |
| **Stable Audio Open 1.0** | Sound effect generation | Created sound effects for enemy attacks and skills |
| **Unity** | Game engine | Integrated assets, implemented enemy behavior logic, terrain and object placement |
| **Mixamo** | Rigging and animations | Applied animations to enemy models |
| **Blender** | 3D editing | Converted models to FBX, adjusted model size and scale |

---

## 4.Timeline (6 Weeks)

| Week | Goal | Deliverable |
|------|------|------------|
| 1 | Learn Unreal Engine 5, familiarize with the interface and basic prototyping | Basic understanding of UE5 workflow|
| 2 | Project framework & basic scene using Unreal Engine | Movable player prototype, basic hero skill implementation |
| 3 | Transition project to Unity, import assets and set up project | Unity project initialized with UE prototype assets |
| 4 | Core skill (Wave Attack) refinement & basic enemy AI | Playable demo with Wave Attack skill and functional enemy AI |
| 5 | Implement additional skills (Normal Attack, Falling Brick) | At least 2 additional skill branches playable |
| 6 | Skill upgrade system, UI completion, AI-generated content integration (art, sound, models) | Fully playable skill upgrade system, integrated visual/audio assets |


---

## 5. Reflections

## Renkai Reflection

Generative AI tools greatly streamlined our workflow, but creating high-quality AI-generated assets still required significant time for iterative refinement.

Some limitations of the AI tools became apparent during development:

- **3D Model Generation**: For simple objects, like a cube, minimal vertex count is sufficient, yet AI-generated models often lack flexibility in adjusting vertices. Non-humanoid characters could not be automatically rigged, and sometimes the generated rigs had errors or required manual correction.

- **UI Generation**: There is currently no AI model specialized for game UI design. Most tools generate generic images, which are not always suitable for interactive game interfaces.

Overall, while AI served as a powerful assistant for speeding up content creation, **human intervention remained essential** for ensuring technical accuracy, usability, and aesthetic consistency.


---

*Project by Team Rogue Synth*  
🔗 [https://rogue-synth.github.io](https://rogue-synth.github.io)
Assets created during development
🔗[https://drive.google.com/drive/folders/1k0wq6oe_rZ1G_FWIXGu-7K5lyvKph4dH?usp=sharing]
