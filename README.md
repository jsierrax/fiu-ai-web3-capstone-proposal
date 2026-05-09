# AI-Assistant for Intent-Based Blockchain Applications

## FIU Senior Design / Capstone Sponsor Proposal

This repository presents a proposed FIU Senior Design / Capstone project for academic consideration by Dr. Masoud Sadjadi and the Knight Foundation School of Computing & Information Sciences.

The project asks a student team to prototype an AI-assisted interface that helps users understand, compose, inspect, and safely prepare blockchain-related workflows through natural language.

The core academic focus is software engineering, AI systems, distributed infrastructure, cybersecurity, and human-centered design. Blockchain is used as the applied distributed-systems environment, not as a cryptocurrency promotion.

## Prepared For

| Role | Name / Organization |
|---|---|
| Academic reviewer | Dr. Masoud Sadjadi |
| Affiliation | Knight Foundation School of Computing & Information Sciences, College of Engineering & Computing, Florida International University |
| Project originator | Adriano Fiorenza, Founder & Developer, GameChanger Wallet |
| Repository organizer / external sponsor | Juan Sierra, Founder, WebBridges.io |

## At a Glance

| Category | Description |
|---|---|
| Project type | FIU Senior Design / Capstone sponsor proposal |
| Academic focus | AI systems, software engineering, cybersecurity, distributed systems, human-computer interaction |
| Applied domain | Cardano and intent-based blockchain workflows |
| Prototype goal | AI assistant for educational explanations and human-approved workflow drafts |
| Safety boundary | No custody, no seed phrase storage, no autonomous signing |
| Suggested team | 4–5 students |
| External sponsors | GameChanger Wallet and WebBridges.io |

## Project Background
This repository presents an AI + Web3 capstone project designed to make decentralized technologies more accessible through open, intent-based, client-side infrastructure.
The project explores how students, developers, researchers, non-technical users, and AI systems can interact with Cardano-based tools such as GameChanger Wallet, the Universal DApp Connector, GCScript DSL, Retrieval-Augmented Generation, Model Context Protocol, and intent-based workflow generation.
The repository is structured for academic review, software engineering practice, collaboration, version control, and possible FIU Senior Design / Capstone consideration.

## Contents

- [Project Background](#project-background)
- [Project Summary](#project-summary)
- [Problem Statement](#problem-statement)
- [Proposed Solution](#proposed-solution)
- [Academic Fit](#academic-fit)
- [Architecture Overview](#architecture-overview)
- [Security Requirements](#security-requirements)
- [Capstone Scope](#suggested-two-semester-capstone-scope)
- [Expected Deliverables](#expected-deliverables)
- [External Sponsor Support](#external-sponsor-support)
- [Disclaimer](#disclaimer)

---

## Project Summary
This project proposes an AI-assisted, intent-based interface that helps users understand and safely compose blockchain workflows through natural language.
A student team would design and prototype a software system that uses retrieval-augmented generation, tool orchestration, and client-side wallet interaction patterns to translate user requests into clear, reviewable, human-approved workflow drafts.
The system would be designed with strong safety boundaries:
* It does not custody private keys.
* It does not store seed phrases.
* It does not sign transactions on behalf of the user.
* It does not execute financial actions autonomously.
* It does not bypass wallet review.
Instead, the assistant helps users learn, inspect, and prepare decentralized workflows while keeping final approval inside the user-controlled wallet environment.

## Problem Statement
Most users cannot safely interact with decentralized systems because the tooling is technical, fragmented, and difficult to inspect.
Even simple blockchain workflows may require knowledge of wallets, addresses, transactions, scripts, APIs, smart contract models, protocol-specific terminology, and security risks.
This creates barriers for:
* Students
* Developers
* Researchers
* Non-technical users
* Institutions exploring decentralized infrastructure
* AI systems that need safe, structured access to external tools
The educational opportunity is to ask students to design a system where AI reduces complexity without removing user agency.

## Proposed Solution
The student team would prototype a Cardano-focused AI assistant capable of:
1. Answering user questions using a curated knowledge base.
2. Explaining selected blockchain workflows in plain language.
3. Translating natural-language requests into structured workflow drafts or intents.
4. Preparing human-readable previews of generated workflows.
5. Maintaining clear trust boundaries between the AI assistant, external tools, wallet environment, and user approval.
6. Demonstrating safe human-in-the-loop patterns where the AI suggests and explains, but the user reviews and approves.
The initial applied domain is Cardano, with optional exploration of GameChanger Wallet’s Universal DApp Connector and GCScript DSL as an intent-based, client-side workflow layer.

## Academic Fit
This project may be appropriate for students in:
* Computer Science
* Data Science / AI
* Cybersecurity
* Information Technology
* Computer Engineering
* Internet of Things
* Interdisciplinary Engineering or Computing tracks
The core academic challenge is software engineering, not cryptocurrency promotion.
Students would practice:
* Requirements analysis
* AI/RAG implementation
* Modular tool orchestration
* Secure software design
* Distributed systems thinking
* Human-computer interaction
* Technical documentation
* Testing and validation
* Final showcase demonstration

## Architecture Overview
The prototype should separate four layers:
### 1. User Interaction Layer
The interface where users ask questions, review explanations, and inspect generated workflows.
### 2. AI and Retrieval Layer
The system that retrieves trusted context, explains concepts, and generates structured drafts.
### 3. Tool and Intent Layer
The system that prepares machine-readable workflow outputs or intent structures.
### 4. Wallet and Approval Layer
The user-controlled environment where any wallet-impacting action must be reviewed and approved by the user.

## Technical Components
Suggested components include:
* Large Language Model interface
* Retrieval-Augmented Generation knowledge base
* Tool orchestration layer
* MCP-style interface or comparable modular tool architecture
* Cardano educational and technical data sources
* Intent generation and validation logic
* Optional GameChanger Wallet / GCScript workflow integration
* Web-based chat or assistant interface
* Human-readable workflow explanation module
* Security and trust-boundary documentation
The final implementation should be adjusted based on FIU faculty guidance and student team capacity.

## Security Requirements
Security and user sovereignty are core design requirements.
The assistant must not:
* Custody private keys
* Store seed phrases
* Sign transactions on behalf of the user
* Execute financial actions autonomously
* Bypass wallet review
* Misrepresent risks to the user
* Hide generated workflow logic from the user

The assistant should:
* Explain generated workflows clearly
* Separate educational guidance from executable workflow drafts
* Require explicit user approval for wallet-impacting actions
* Validate generated intents before wallet handoff
* Show assumptions, limitations, and potential risks
* Include prompt-injection and tool-misuse testing
* Document trust boundaries between AI, external tools, wallet environment, and user approval
In this architecture:
> The AI assistant suggests, explains, and prepares.
> The wallet environment protects, validates, and signs.
> The user reviews, decides, and approves.

## Suggested Two-Semester Capstone Scope
### Senior Design I: Research, Architecture, and Prototype Planning
Expected outputs:
* Requirements analysis
* Literature and technology review
* System architecture diagram
* Trust-boundary and threat model
* Curated knowledge base design
* Prototype user flows
* Initial AI/RAG proof of concept
* Evaluation plan
* Final implementation roadmap
### Senior Design II: Implementation, Testing, and Showcase Demonstration

Expected outputs:
* Working assistant prototype
* Knowledge retrieval and response workflow
* Intent generation workflow
* Human-readable explanation layer
* Required wallet-backed intent integration demo. A working demo showing that the system can translate a user intent into an actionable Cardano workflow and complete the interaction through GameChanger Wallet, including wallet connection, user review/signing, and a visible execution result.
* Security testing and validation checklist
* User testing or usability feedback
* Final technical report
* Poster, presentation, and live demonstration

## Suggested Student Team Roles

| Role                        | Primary Responsibility                                                                 |
| --------------------------- | -------------------------------------------------------------------------------------- |
| AI/RAG Lead                 | Knowledge base, retrieval pipeline, answer quality, and evaluation                     |
| Tool Orchestration Lead     | Modular tool interface, MCP-style architecture, and API/tool integration               |
| Blockchain Integration Lead | Cardano workflows, intent structures, and optional GameChanger/GCScript integration    |
| Security & Trust Lead       | Threat model, prompt-injection testing, permission boundaries, and safety requirements |
| UX/Product Lead             | Chat interface, review screens, user testing, documentation, and final demo narrative  |


## Example Demonstration Flow
A final showcase demonstration could show this sequence:
1. A user asks: “Help me understand staking on Cardano and prepare a safe example delegation workflow.”
2. The assistant explains the concept using curated sources.
3. The assistant generates a structured draft workflow or intent.
4. The system explains the workflow in plain language.
5. The user reviews assumptions, risks, and next steps.
6. Optional wallet handoff occurs only after user review.
7. The team presents a trust-boundary diagram showing what the AI suggests, what tools process, what the wallet controls, and what the user must approve.

## Expected Deliverables
The student team would aim to deliver:
1. Functional prototype or proof of concept
2. Technical architecture documentation
3. Curated knowledge base and retrieval workflow
4. Demonstration workflows
5. Human-readable workflow explanation interface
6. Intent-generation or wallet-handoff demo, if feasible
7. Security and trust model analysis
8. Prompt-injection and tool-misuse testing checklist
9. Setup and usage documentation
10. Open-source repository or equivalent project repository
11. Final technical report
12. Poster, presentation, and live demonstration

## Proposed Success Criteria
The project would be considered successful if students can demonstrate:
* A working AI assistant prototype
* Accurate answers from a curated knowledge base
* At least three blockchain-related educational or workflow scenarios
* Clear human-readable explanations of generated workflows
* Strong separation between AI suggestion and user-approved execution
* No private key custody or autonomous transaction signing on behalf of the user
* Multisig-friendly design considerations for user-approved execution
* Documented threat model and security testing approach
* A polished final presentation suitable for FIU Senior Design Showcase
## Recommended Repository Structure

```text
.
├── README.md
├── docs/
│   ├── proposal.md
│   ├── architecture.md
│   ├── threat-model.md
│   ├── research-notes.md
│   └── showcase-demo.md
├── references/
│   └── sources.md
├── prototypes/
│   └── README.md
├── examples/
│   ├── user-flows.md
│   └── sample-intents.md
├── SECURITY.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
└── LICENSE
```

## External Sponsor Support
 GameChanger Wallet and WebBridges.io can support the student team by providing:
* Project concept and domain framing
* Weekly mentorship availability
* Technical context for Cardano and intent-based workflows
* Sample use cases and demo scenarios
* Documentation references
* Feedback on prototype direction
* Review of final demonstration workflows
* Support for aligning the project with real-world usability needs
The sponsors are open to adjusting the technical depth and scope based on FIU faculty guidance, course expectations, and student team capacity.

## Resource Needs
Potential resources may include:
* LLM API credits or local model alternatives
* Development hosting environment
* Testnet blockchain access
* Documentation and sample workflows
* Optional GameChanger Wallet test environment
* GitHub repository or equivalent project repository
* Faculty guidance on academic requirements and grading expectations

The project can be scoped to avoid the use of real funds and should operate in testnet, simulated, or educational environments wherever appropriate.

## Contributors and Roles
This repository is organized for academic review, collaboration, and possible FIU Senior Design / Capstone consideration.
Concept and technical direction:
- **Adriano Fiorenza** — Founder & Developer, GameChanger Wallet
Academic framing, GitHub organization, and ecosystem coordination:
- **Juan Sierra** — Founder, WebBridges.io

---

## Disclaimer
This repository is for academic project proposal and educational prototyping purposes only.
It is not financial advice, legal advice, investment guidance, or a production wallet application.
Any student implementation should use testnet, simulated, or educational environments unless explicitly approved otherwise by FIU faculty and project sponsors.
