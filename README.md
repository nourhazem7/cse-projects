# CSE Projects — Nour Hazem Mohsen

A collection of software and hardware projects built during my Computer Science Engineering degree at the **German University of Cairo**. Spans database internals, full-stack web, embedded systems, hardware simulation, and OS-level programming.

---

## Contents

| # | Project | Domain | Tech |
|---|---------|--------|------|
| 1 | [Database Engine](#1-database-engine) | Databases | Java, SQL |
| 2 | [CampusConnect Web App](#2-campusconnect-full-stack-web-application) | Full-Stack Web | React, Node.js, REST APIs |
| 3 | [Anime Battle Game](#3-anime-battle-game) | GUI / OOP | Java, JavaFX |
| 4 | [Basic Computer Simulation](#4-basic-computer-simulation) | Digital Logic | Logisim |
| 5 | [Embedded Escape Room Station](#5-embedded-systems-escape-room-station) | Embedded Systems | C, RP2040, Pico SDK |
| 6 | [Mini Autonomous Car — FPGA](#6-mini-autonomous-car--fpga) | Hardware / FPGA | Verilog, Quartus, ModelSim |
| 7 | [OS Process Scheduler Simulation](#7-os-process-scheduler-simulation) | Operating Systems | C, pthreads |
| 8 | [Tomasulo Algorithm Simulator](#8-tomasulo-algorithm-simulator) | Computer Architecture | Java, MIPS, GUI |

---

## Projects

### 1. Database Engine
`Java` `SQL` `Data Structures`

Built a database engine from scratch in Java supporting SQL-based table creation, insertion, and deletion with sorted data handling. Designed and implemented a **sparse indexing system** to optimize search performance, and coded full DDL/DML operations for efficient data management and retrieval.

**Key concepts:** B-tree-style indexing, sorted storage, query parsing, DDL/DML

📁 [`Databases/Database-Engine-Development`](Databases/Database-Engine-Development)

---

### 2. CampusConnect — Full-Stack Web Application
`React` `Node.js` `REST APIs` `Git`

Full-stack web application supporting campus activities and interactions. Backend handles application logic, data storage, and API endpoints; frontend delivers a responsive interface with modern UI/UX principles. Built collaboratively with Git version control, extensive commit history, and iterative feature integration.

**Key concepts:** Client-server separation, real-time data handling, REST API design, collaborative development

🔗 [github.com/Advanced-Computer-Lab-2025/CampusConnect1](https://github.com/Advanced-Computer-Lab-2025/CampusConnect1)  
📁 [`Fullstack/CampusConnect-Fullstack-Web-Application`](Fullstack/CampusConnect-Fullstack-Web-Application)

---

### 3. Anime Battle Game
`Java` `JavaFX` `OOP`

Fully playable 2D desktop game built with Java and JavaFX, simulating anime-style character battles. Implements core game logic including state management, combat mechanics, and event handling — all within a single application architecture. Object-oriented design ensures modularity and maintainability.

**Key concepts:** OOP design patterns, game state machines, event-driven GUI, JavaFX rendering

📁 [`GUI-Applications/Anime-Game-Java-JavaFX`](GUI-Applications/Anime-Game-Java-JavaFX)

---

### 4. Basic Computer Simulation
`Logisim` `Digital Logic` `Computer Architecture`

Simulated a simplified computer architecture in Logisim, including memory units and an ALU. Designed digital circuits with both combinational and sequential logic to model instruction processing and data flow.

**Key concepts:** ALU design, memory units, combinational vs sequential logic, instruction cycle

📁 [`Systems-and-Hardware/Basic-Computer-Simulation-Logisim`](Systems-and-Hardware/Basic-Computer-Simulation-Logisim)

---

### 5. Embedded Systems Escape Room Station
`C` `RP2040` `Pico SDK` `Embedded Systems`

Complete embedded station built as part of an escape room scenario across multiple milestones — covering microcontroller setup, hardware fabrication, system modeling, and full software–hardware integration. Custom drivers developed for sensors and actuators with proper abstraction layers. Station logic governed by a **state-based model** supporting concurrency, hierarchy, and error handling. Final implementation includes hardware enclosure design, calibrated components, and safe power distribution for repeated live demonstrations.

**Key concepts:** RP2040 microcontroller, Pico SDK, state machines, concurrent embedded control, sensor/actuator drivers, hardware enclosure

🔗 [All milestones — code, reports, and demo videos](https://drive.google.com/drive/folders/1fJORXtJAomRTC7-0BG8aNTH04QKQxcDL?usp=sharing)  
📁 [`Systems-and-Hardware/EmbeddedSystems-Escape-Room-Station`](Systems-and-Hardware/EmbeddedSystems-Escape-Room-Station)

---

### 6. Mini Autonomous Car — FPGA
`Verilog` `Quartus` `ModelSim` `FPGA`

Mini autonomous car system programmed on an FPGA using Verilog. Integrates sensors and motors to control movement and implements the hardware-software interface through embedded systems logic. Simulated and verified in ModelSim before deployment.

**Key concepts:** Verilog RTL design, FPGA programming, sensor-motor integration, hardware simulation

📦 [`ZIP-Files/MiniCarProject.zip`](ZIP-Files/MiniCarProject.zip)

---

### 7. OS Process Scheduler Simulation
`C` `pthreads` `Operating Systems`

Process scheduler simulation implementing **FCFS, Round Robin, and Multilevel Feedback Queue** algorithms. Manages fixed-size memory with mutual exclusion enforced via custom mutexes. Includes a real-time GUI to visualize process execution and system state as the scheduler runs.

**Key concepts:** Scheduling algorithms, pthreads, mutex/synchronization, memory management, real-time visualization

📦 [`ZIP-Files/OperatingSystemsSchedulersProject.zip`](ZIP-Files/OperatingSystemsSchedulersProject.zip)

---

### 8. Tomasulo Algorithm Simulator
`Java` `Computer Architecture` `MIPS` `GUI`

GUI-based simulator for the **Tomasulo dynamic scheduling algorithm**, executing MIPS-like assembly instructions cycle by cycle. Visualizes instruction issue, execution, and write-back while tracking reservation stations, buffers, register files, cache state, and the common data bus. Correctly handles RAW, WAR, and WAW data hazards, address conflicts, and simultaneous write-back. Cache behavior is fully configurable — cache size, block size, hit latency, miss penalty, and miss types (compulsory and conflict). Users can configure instruction latencies, station sizes, buffer capacities, and initial register values before simulation begins.

**Key concepts:** Tomasulo algorithm, out-of-order execution, data hazards, instruction-level parallelism, cache modeling, MIPS simulation

📦 [`ZIP-Files/TomasuloSimulatorProj.zip`](ZIP-Files/TomasuloSimulatorProj.zip)

---

## Tech Stack Overview

**Languages:** Java · C · Verilog · JavaScript · Python  
**Web:** React · Node.js · REST APIs  
**Embedded:** RP2040 · Pico SDK · Pico C SDK  
**Hardware:** Logisim · Quartus · ModelSim · FPGA  
**Tools:** Git · GitHub · JavaFX · pthreads

---

## About

**Nour Hazem Mohsen** — CS Engineering student, German University of Cairo (2022–2027)  
