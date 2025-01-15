# SIMOS: Simulation Operating System for AI Agents

Welcome to the **SIMOS** repository! SIMOS (Simulation Operating System) is a powerful AI Simulation Operating System designed to manage and operate AI Agents within simulated and real-world environments. It acts as the brain behind AI companions, enabling them to interact intelligently within games and other applications. This README provides an overview of SIMOS, its architecture, features, implementation examples, and how you can get started.

## Overview

SIMOS is at the heart of the SIPHER//AGI ecosystem. It's built to empower developers to create sophisticated AI Agents capable of learning, adapting, and interacting in complex environments. SIMOS handles everything from processing real-time game states to managing agent memories and decision-making processes. It bridges the gap between advanced AI models (LLMs) and interactive applications like games, providing a seamless integration that brings AI companions to life.

## Glossary

To help you navigate the terminology used in this project, here's a glossary of key terms:

*   **SIPHER//AGI**: A platform designed to foster collaboration between humans and AI, starting with gaming.
*   **AI Agent/Gaming Agent/AI Companion**: Refers to AI entities like KAIO, designed to interact within game environments.
*   **Gaming AI Framework**: The underlying framework used to build AI Agents for gaming.
*   **MOONBASE**: A discovery and trading platform for AI Agents developed by SIPHER//AGI.
*   **SIMOS (Simulation Operating System)**: The core system that manages and operates AI Agents.
*   **KAIO**: The first Gaming Agent developed by SIPHER//AGI, operating under SIMOS.
*   **AUTOMA**: AI companions in Sipher Odyssey, powered by Utility AI within Unreal Engine.
*   **Smart Object**: Interactive elements within Unreal Engine that AI Agents can interact with.
*   **Utility AI**: A custom AI decision-making implementation used by SIPHER//AGI for more dynamic AI behaviors.

## Architecture

SIMOS is designed with a modular architecture that allows for flexibility and scalability. Below are visual representations of the Gaming Agent Prototype and the public SIMOS architecture.

**Gaming Agent Prototype Architecture (January 3, 2025):**

![SIPHER GAME AGENT ROUGH ARCHITECTURE](https://prod-files-secure.s3.us-west-2.amazonaws.com/a29d0ad0-5c40-46dc-afd9-2ba0cc23a350/f9586860-ceb8-48fb-a0cc-ebca371a8e7c/SIPHER_GAME_AGENT_ROUGH_ARCHITECTURE.jpg)

**Public SIMOS Architecture (January 8, 2025):**

![SIMOS Architecture](https://prod-files-secure.s3.us-west-2.amazonaws.com/a29d0ad0-5c40-46dc-afd9-2ba0cc23a350/1bc0bcfa-9e39-4538-a30c-9e33f5bbd457/SIMOS_Architecture.jpg)

**Key Architectural Components**:

1.  **Interface with Game Engine (Unreal Engine)**: SIMOS communicates with the game engine to receive real-time state updates and send commands.
2.  **Large Language Model (LLM) Integration**: LLMs act as the "brain" of the AI Agents, processing information and making decisions.
3.  **Knowledge Base**: A repository of information about the game, including Smart Object definitions, game rules, and sample LLM interactions, used to inform the LLM.
4.  **Agent Memory System**: Allows AI Agents to remember past interactions and learn from them.
5.  **Real-time State Tracking**: Monitors the state of AI Agents and the game environment.

## Features

SIMOS boasts a range of features designed to enhance the capabilities of AI Agents. Here are some of the key features:

### Current Features (as of January 14, 2025)

*   **Agent Memory System**: Enables AI Agents to retain information about past interactions, allowing for more personalized and engaging experiences.
*   **Real-Time KAIO Agent State Tracking (To Do)**:  Provides live monitoring of AI Agent states, offering insights into their performance and status.
*   **Integration with Moonbase**: While primarily focused on SIMOS, the system is designed to be compatible with Moonbase, the platform for showcasing and sharing AI Agents.

### Future Potential Features

*   **Enhanced LLM Integration**: Deeper integration with various LLM models (e.g., Gemini, Claude, GPT-4o, DeepSeek v3) to enhance decision-making and natural language understanding.
*   **Advanced Agent Customization**: Allowing developers and users to fine-tune AI Agent personalities, behaviors, and abilities.
*   **Dynamic Content Creation**: Leveraging AI to generate new content, such as quests, dialogues, and storylines.
*   **Cross-Game Compatibility**: Expanding SIMOS to support AI Agents in a variety of games beyond Sipher Odyssey.

## Implementation Examples / Use Cases

SIMOS powers a variety of AI-driven features and interactions within games. Here are some examples of how SIMOS is currently being used and envisioned for future applications:

### KAIO in Sipher Odyssey

KAIO is the flagship AI Agent developed using SIMOS, showcasing its capabilities within the Sipher Odyssey game.

*   **AI Livestream Solo Play**: KAIO can autonomously play Sipher Odyssey, demonstrating strategic decision-making and adaptability. (PIC: Dat Tran Thanh - Delivered: January 14, 2025)
*   **Moonbase Interaction**: KAIO interacts with the Moonbase environment, responding to user inputs and demonstrating dynamic behaviors.

    *   **Teaser Clip**: [Sipher Moonbase Teaser](https://prod-files-secure.s3.us-west-2.amazonaws.com/a29d0ad0-5c40-46dc-afd9-2ba0cc23a350/53710b70-da62-4b7a-a99c-f8f77e530d45/Sipher_Moonbase_Teaser.mov)
    *   **In-Engine Terminal Output**:
        ![Moonbase Terminal Output](https://prod-files-secure.s3.us-west-2.amazonaws.com/a29d0ad0-5c40-46dc-afd9-2ba0cc23a350/8ad6e62a-b626-4701-bc7d-1ea0a79a19b7/image.png)
    *   **PIC**: Dat Tran Thanh (Incubation), Hải Huỳnh (Technical Artist)

*   **AI vs AI Colosseum**: KAIO can participate in battles against other AI Agents, providing a spectacle for players and valuable data for developers.

    *   **GIF**:
        ![AI vs AI Colosseum](https://prod-files-secure.s3.us-west-2.amazonaws.com/a29d0ad0-5c40-46dc-afd9-2ba0cc23a350/e5b88d47-291a-463b-9d72-58ba19dc738a/aaaa.gif)
    *   **Video**: [Colosseum AI vs AI](https://prod-files-secure.s3.us-west-2.amazonaws.com/a29d0ad0-5c40-46dc-afd9-2ba0cc23a350/114046b9-a274-4141-a25c-afe32c6202c4/COLOSSEUM_AI_VS_AI.mov)

*   **Game Automation**: KAIO can automate tasks within Sipher Odyssey based on user chat commands, such as farming rewards, completing quests, and providing progress reports.

    *   **Screenshot**:
        ![KAIO Automation](https://prod-files-secure.s3.us-west-2.amazonaws.com/a29d0ad0-5c40-46dc-afd9-2ba0cc23a350/10c79ecb-c37a-40fc-a244-4ff9b8defd2a/KO_page.png)

*   **Question & Answer Agent**: KAIO acts as a knowledgeable guide, answering player questions about the game, providing strategic advice, and even offering economic insights within the Sipher ecosystem.

    *   **Screenshot**:
        ![KAIO Q&A](https://prod-files-secure.s3.us-west-2.amazonaws.com/a29d0ad0-5c40-46dc-afd9-2ba0cc23a350/14130a77-9262-469f-ba38-67bee5d26d63/STRIFE.png)

### LLM and Game Engine Interaction

SIMOS facilitates a powerful interaction between LLMs and the game engine. Here's a breakdown of the process:

1.  **Game State Declaration**: Smart Objects and their possible states are defined in Unreal Engine and stored in the Knowledge Base. (Code examples are available in the full document).
2.  **LLM Input & Output Examples**: Sample interactions are provided to the LLM, demonstrating how to interpret game state changes and generate appropriate responses, intentions, and reasoning. (Code examples and explanations are available in the full document).
3.  **Real-time Updates**: When GameStates change, Unreal Engine sends updates to the LLM via SIMOS.
4.  **LLM Processing**: The LLM processes the updates using the General System Prompt and the Sipher Odyssey-specific Knowledge Base.
5.  **Command Generation**: The LLM generates commands for the Unreal Engine, directing AI Agent actions and influencing the game world.

## How to Use/Setup/Deploy

(This section will be expanded as the project evolves. Currently, detailed setup and deployment instructions are under development.)

**Prerequisites:**

*   Unreal Engine (Specific version to be determined)
*   Access to necessary LLMs (e.g., API keys for Gemini, Claude, GPT-4o)
*   (Other dependencies will be listed here)

**Basic Setup:**

1.  Clone this repository:

    ```bash
    git clone [repository URL]
    ```
2.  (Further instructions for integrating with Unreal Engine, configuring LLMs, and deploying SIMOS will be added here).

## Overview of Sipher//AGI

SIPHER//AGI is an ambitious project aimed at revolutionizing the interaction between humans and AI, particularly within the gaming world. It envisions a future where AI companions are integral to the gaming experience, offering personalized interactions, dynamic challenges, and new levels of immersion. SIMOS is a core component of this vision, providing the technological foundation for creating and managing sophisticated AI Agents. Other key parts of the ecosystem include:
* **Moonbase**: AI Agent discovery and trading platform.
* **KAIO**: The first AI Gaming Agent developed by Sipher//AGI.
* **Sipher Odyssey**: Action RPG game developed by Sipher//AGI, as a testing ground for many of the core features.

## Contributing

We welcome contributions from the community! If you're interested in contributing to SIMOS, please reach out to Tin Nguyen (CEO) or Susan Pham (Metaverse - PD). We are particularly interested in contributions in the following areas:

*   LLM integration and optimization
*   Unreal Engine development
*   AI Agent design and development
*   Documentation and tutorials

## License

(Specify your project's license here)

## Contact

For any inquiries or further information, please contact:

*   Tin Nguyen (CEO) - @Tin Nguyen
*   Susan Pham (Metaverse - PD) - @Susan Pham

---

**Document Status**: Ongoing

**Document Update PIC**: @Tin Nguyen (CEO), @Susan Pham (Metaverse - PD)
