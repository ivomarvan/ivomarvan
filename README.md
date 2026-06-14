# Hi there! I'm Ivo Marvan 👋

I am a Python engineer with a passion for AI, AI-driven development, concurrency, and image processing.

I also have extensive experience in developing hardware and software prototypes, specializing in C/C++ for ESP32 & ESP-IDF. 
I enjoy working with communication protocols like CAN Bus, UART, I2C, and SPI, and integrating various sensors and devices such as GPS, LiDAR, etc.

---

## 🛠️ Featured Projects

Here is a curated list of projects I have designed and built:

### [Agentflow-kit](https://github.com/ivomarvan/agentflow-kit)

<a href="https://github.com/ivomarvan/agentflow-kit"><img src="https://raw.githubusercontent.com/ivomarvan/agentflow-kit/refs/heads/master/img/agentflow-kit_illustration_1.jpg" height="120" align="right" alt="Agentflow-kit" /></a>

A lightweight, educational framework for building LLM agent workflows using a declarative state graph with deterministic Bulk Synchronous Parallel (BSP) execution. 

This project demonstrates a deep understanding of complex AI orchestration by solving the notorious "black box" debugging problem common in modern agent frameworks. By enforcing strict immutability and predictable execution cycles, it provides a robust, testable, and transparent architecture.
* **Deterministic Execution:** Uses a fixed Compute → Barrier → Apply cycle (BSP model) for predictable and reproducible agent traces.
* **Immutable State:** State is a frozen dataclass with explicit patches and typed reducers, preventing parallel nodes from silently overwriting each other.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=flat-square&logo=vue.js&logoColor=4FC08D)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&logoColor=white)
![AI Agents](https://img.shields.io/badge/AI_Agents-LLM_Orchestration-blueviolet?style=flat-square)
![State Machine](https://img.shields.io/badge/State_Machine-BSP_Execution-orange?style=flat-square)

<br clear="right"/>

---

### [Cursor Best Practices Template](https://github.com/ivomarvan/cursor-best-practices-template)

<a href="https://github.com/ivomarvan/cursor-best-practices-template"><img src="https://github.com/ivomarvan/cursor-best-practices-template/raw/master/img/cursor-best-practices-template.jpg" height="120" align="right" alt="Cursor Best Practices Template" /></a>

A shared Cursor IDE configuration library containing curated `.mdc` rules and agent skills that enforce consistent coding standards and best practices across projects.

* **Agentic Project Management (APM):** Implements a structured workflow dividing AI tasks into roles: **Planner** (high-context reasoning models), **Coder** (fast implementation models), and **Human** (Tech Lead oversight).
* **Automated Quality:** Enforces strict boundaries, Clean Code, SOLID principles, automated linting/formatting (Ruff, ESLint), and strict type checking.

![Cursor](https://img.shields.io/badge/Cursor-AI_IDE-blue?style=flat-square)
![Markdown](https://img.shields.io/badge/Markdown-%23000000.svg?style=flat-square&logo=markdown&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=flat-square&logo=git&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=flat-square&logo=vue.js&logoColor=4FC08D)

<br clear="right"/>

---

### [Veilgit](https://github.com/ivomarvan/veilgit)

<a href="https://github.com/ivomarvan/veilgit"><img src="https://github.com/ivomarvan/veilgit/raw/master/img/veilgit.1.600x450.png" height="120" align="right" alt="Veilgit" /></a>

A Python tool that adds transparent file encryption to any git repository — selected files stay readable locally but are encrypted before they reach the remote repository.

* **How it works:** Leverages git's native `clean`/`smudge` filter mechanism using [age](https://github.com/FiloSottile/age) encryption — you use git exactly as before, requiring no workflow changes.
* **Key Features:** Pattern-based file selection, multi-recipient collaboration, ensures only encrypted data is stored in the git history (plaintext never leaves your machine), and an interactive setup wizard with multi-language support (EN, DE, FR, ES, CS, PL).

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=flat-square&logo=git&logoColor=white)
![age](https://img.shields.io/badge/age-Encryption-green?style=flat-square)
![Security](https://img.shields.io/badge/Transparent_Encryption-Privacy-blueviolet?style=flat-square)

<br clear="right"/>

---

### [Concurrent Harmony](https://github.com/ivomarvan/ConcurrentHarmony)

<a href="https://github.com/ivomarvan/ConcurrentHarmony"><img src="https://github.com/ivomarvan/ConcurrentHarmony/raw/master/img/ConcurrentHarmony.jpg" height="120" align="right" alt="Concurrent Harmony" /></a>

*Where Threads and Processes Sing Together.* A comprehensive Python framework for managing concurrency in applications involving multiple processes and threads.

* **Real-world Origin:** Developed for high-parallelism sensor data logging (GPS, CAN bus, rangefinder) on Raspberry Pi 4b aboard drones at [Zuri.com](https://zuri.com), with the kind permission of Michal Illich.
* **Key Features:** Supports multi-threading/multi-processing, advanced signal management (standard & user-defined signals), state persistence via files, and Tkinter-based GUI integration for process control.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberry-pi&logoColor=white)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-blue?style=flat-square)
![Concurrency](https://img.shields.io/badge/Concurrency-Multiprocessing_/_Multithreading-orange?style=flat-square)

<br clear="right"/>

---

### [Astriot](https://github.com/ivomarvan/astriot)

<a href="https://github.com/ivomarvan/astriot"><img src="img/astriot.jpg" height="120" align="right" alt="Astriot" /></a>

*Affordable image processing for assistive technologies.* A concept and library designed to extract facial and body pose data, providing text outputs via an API.

* **Live Demo / Info:** Visit the [Astriot Website](https://ivomarvan.github.io/astriot/)
* **Purpose:** Enables affordable, lightweight image processing for accessibility and other sensor-driven applications.

![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=flat-square&logo=javascript&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=flat-square&logo=vue.js&logoColor=4FC08D)
![Image Processing](https://img.shields.io/badge/Computer_Vision-Pose_Estimation-green?style=flat-square)
![Assistive Tech](https://img.shields.io/badge/Assistive_Tech-Accessibility-blueviolet?style=flat-square)

<br clear="right"/>

---

### [idf-can-bus (ESP32 + CAN Bus Solutions)](https://github.com/idf-can-bus)

<a href="https://github.com/idf-can-bus"><img src="https://github.com/idf-can-bus/mcp25xxx-multi-idf-can/raw/master/doc/ESP32_MCP2515_CAN_steampunk400x400.png" height="120" align="right" alt="ESP32 CAN Bus Solutions" /></a>

A dedicated GitHub organization containing a collection of modular, production-ready CAN libraries for ESP32 platforms using ESP-IDF.

* **[can-multibackend-idf](https://github.com/idf-can-bus/can-multibackend-idf):** Multi-Backend CAN Example Suite. Seamlessly switch between built-in TWAI and external MCP25xxx controllers over SPI.
* **[twai-idf-can](https://github.com/idf-can-bus/twai-idf-can):** Simplified high-level adapter for ESP32's built-in TWAI (CAN) controller with automatic error recovery.
* **[mcp25xxx-multi-idf-can](https://github.com/idf-can-bus/mcp25xxx-multi-idf-can):** Extended CAN driver supporting multiple MCP2515 controllers over SPI.
* **[examples-utils-idf-can](https://github.com/idf-can-bus/examples-utils-idf-can):** Common utility functions shared across the CAN examples.

![C](https://img.shields.io/badge/C-%2300599C.svg?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=flat-square&logo=c%2B%2B&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-%23E7352C.svg?style=flat-square&logo=espressif&logoColor=white)
![ESP-IDF](https://img.shields.io/badge/ESP--IDF-Espressif-red?style=flat-square)
![CAN Bus](https://img.shields.io/badge/CAN_Bus-Automotive_/_Industrial-blue?style=flat-square)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-Real--Time_OS-green?style=flat-square)

<br clear="right"/>

---
