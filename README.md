<div align="center">

# MarkSoft

### Cybersecurity · Ethical Hacking · Reverse Engineering · .NET · Automation

Разрабатываю инструменты, исследую приложения и протоколы, автоматизирую рутинные процессы и изучаю безопасность программных систем.

[![Website](https://img.shields.io/badge/Эрида-24erida.ru-6366F1?style=for-the-badge)](https://24erida.ru)
[![Telegram](https://img.shields.io/badge/Telegram-Mark__Soft-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Mark_Soft)
[![GitHub](https://img.shields.io/badge/GitHub-marksoft1993-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/marksoft1993)

</div>

---

## Обо мне

Я разработчик, интересующийся пересечением нескольких направлений:

**Cybersecurity, Ethical Hacking, Reverse Engineering, .NET-разработка, Computer Vision и Automation.**

Мне особенно интересно понимать, **как приложения устроены изнутри**: как взаимодействуют клиент и сервер, как работают сетевые протоколы, нативные библиотеки, процессы, память приложения и механизмы защиты.

В разработке основной стек — **VB.NET / .NET**, **AvaloniaUI**, **ADB**, **YOLO** и инструменты анализа программного обеспечения.

Помимо создания приложений, занимаюсь исследованием безопасности в рамках собственных систем, лабораторных сред, CTF и других разрешённых сценариев.

Основной долгосрочный проект — **«Эрида»**, десктопный ассистент для Kingdom Guard, объединяющий автоматизацию, компьютерное зрение, Android-интеграцию и собственную архитектуру выполнения сценариев.

---

# 🛡 Cybersecurity & Ethical Hacking

Одно из основных направлений моей работы — исследование безопасности программного обеспечения.

Мне интересен не только поиск отдельных уязвимостей, но и понимание всей архитектуры приложения:

```text
Application
    ↓
Network Protocols
    ↓
Authentication
    ↓
Native Libraries
    ↓
Memory
    ↓
Runtime
    ↓
Operating System
```

Работаю исключительно с системами, для которых имеется разрешение на исследование, собственными приложениями и лабораторными средами.

### Основные направления

- **Application Security**
- **Ethical Hacking**
- **Reverse Engineering**
- **Network Protocol Analysis**
- **Android Security**
- **Dynamic Analysis**
- **Memory Analysis**
- **API Security**
- **Authentication Flow Analysis**
- **Binary Analysis**
- **Security Research**

---

## 🔍 Reverse Engineering

Изучаю внутреннее устройство приложений и способы взаимодействия между различными компонентами системы.

Работаю с:

- PE / ELF-бинарниками;
- DLL и нативными библиотеками;
- Android APK;
- IL2CPP-приложениями;
- Unity-приложениями;
- managed и native кодом;
- runtime-анализом;
- структурами памяти;
- сетевыми протоколами;
- сериализацией данных;
- клиент-серверным взаимодействием.

Основная цель анализа — восстановить архитектуру приложения и понять поток данных:

```text
Client
   │
   ├── UI
   ├── Game Logic
   ├── Native Code
   ├── Runtime
   │
   ├── Network Layer
   │      │
   │      ├── HTTP / HTTPS
   │      ├── TCP
   │      └── Custom Protocols
   │
   └── Server
```

### Инструменты

![Ghidra](https://img.shields.io/badge/Ghidra-Reverse_Engineering-B91C1C?style=flat-square)
![Frida](https://img.shields.io/badge/Frida-Dynamic_Instrumentation-EAB308?style=flat-square)
![IL2CPP](https://img.shields.io/badge/IL2CPP-Analysis-7C3AED?style=flat-square)
![ADB](https://img.shields.io/badge/ADB-Android_Debug_Bridge-334155?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-Network_Analysis-1679A7?style=flat-square&logo=wireshark&logoColor=white)

Использую и изучаю:

- **Ghidra**
- **Frida**
- **Il2CppDumper**
- **AssetStudio**
- **APKTool**
- **ADB**
- **Wireshark**
- Android debugging tools
- статический и динамический анализ

---

# 🌐 Network & Protocol Analysis

Отдельный интерес представляет анализ взаимодействия клиента и сервера.

Исследую:

- HTTP / HTTPS API;
- TCP-соединения;
- бинарные протоколы;
- handshake-процессы;
- request / response модели;
- сериализацию пакетов;
- authentication flow;
- session management;
- encryption layers;
- структуру сетевых сообщений.

Типичный процесс исследования:

```text
Traffic Capture
      ↓
Packet Classification
      ↓
Protocol Reconstruction
      ↓
Authentication Analysis
      ↓
Message Structure
      ↓
Client Implementation
```

Цель — понять протокол и архитектуру системы, а не просто воспроизвести отдельный запрос.

---

# 📱 Android Security

Работаю с Android-приложениями как со стороны автоматизации, так и со стороны анализа.

### Направления

- APK structure;
- Android Debug Bridge;
- Activity / Process analysis;
- native libraries;
- runtime instrumentation;
- emulator environments;
- ARM64 / x86_64;
- application traffic;
- dynamic analysis;
- Unity / IL2CPP Android applications.

Использую реальные Android-устройства и эмуляторы для создания контролируемых исследовательских сред.

---

# 🧠 Dynamic Analysis

Интересует поведение приложения непосредственно во время выполнения.

Исследую:

- загруженные модули;
- runtime addresses;
- native functions;
- memory structures;
- function calls;
- network handlers;
- callbacks;
- serialization / deserialization;
- работу runtime-компонентов.

Для динамического анализа использую в том числе **Frida** и собственные инструменты.

---

# 💻 Software Development

Основной стек разработки — **.NET**.

![VB.NET](https://img.shields.io/badge/VB.NET-512BD4?style=flat-square)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![AvaloniaUI](https://img.shields.io/badge/AvaloniaUI-8B5CF6?style=flat-square)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white)

Работаю с:

- VB.NET;
- .NET Framework;
- .NET;
- WinForms;
- AvaloniaUI;
- многопоточностью;
- асинхронными операциями;
- event-driven архитектурой;
- сетевыми клиентами;
- REST API;
- desktop-инструментами;
- внутренними automation-frameworks.

---

# 👁 Computer Vision

Использую компьютерное зрение как часть систем автоматизации.

![YOLO](https://img.shields.io/badge/YOLO-Computer_Vision-111827?style=flat-square)
![ONNX](https://img.shields.io/badge/ONNX-Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)
![DirectML](https://img.shields.io/badge/DirectML-GPU_Inference-0078D4?style=flat-square)

Работаю с:

- **YOLO**
- object detection;
- dataset preparation;
- image annotation;
- model training;
- ONNX;
- DirectML;
- real-time inference;
- object tracking;
- image preprocessing;
- UI element detection.

Один из вариантов архитектуры моих систем автоматизации:

```text
Screen Capture
      ↓
YOLO Detector
      ↓
Object Tracking
      ↓
State Recognition
      ↓
Decision Engine
      ↓
Automation Action
```

Таким образом автоматизация принимает решения не только по координатам, а на основе текущего визуального состояния приложения.

---

# 🤖 Automation

Создаю системы, способные самостоятельно выполнять последовательности действий и реагировать на изменение состояния приложения.

### Основные задачи

- Android automation через ADB;
- управление эмуляторами;
- screenshot processing;
- UI recognition;
- сценарии действий;
- очереди задач;
- управление несколькими устройствами;
- автоматическое восстановление после ошибок;
- state machines;
- event-driven automation.

Типовая архитектура:

```text
Device
  ↓
ADB
  ↓
Screen Capture
  ↓
Computer Vision
  ↓
State Detection
  ↓
Decision Engine
  ↓
Script
  ↓
Action
```

---

# 🧰 Технологический стек

| Направление | Технологии |
| :--- | :--- |
| 🛡 Cybersecurity | Application Security, Ethical Hacking, Security Research |
| 🔍 Reverse Engineering | Ghidra, Frida, Il2CppDumper, APKTool, AssetStudio |
| 🌐 Network Analysis | HTTP/HTTPS, TCP, API Analysis, Protocol Reconstruction |
| 📱 Android | ADB, APK, Android Runtime, ARM64, x86_64 |
| 💻 Development | VB.NET, .NET, .NET Framework |
| 🖥 Desktop UI | AvaloniaUI, WinForms |
| 👁 Computer Vision | YOLO, ONNX, DirectML |
| 🤖 Automation | ADB Automation, State Machines, Script Engines |
| 🎮 Game Technologies | Unity, IL2CPP |
| 🪟 Platforms | Windows, Android, BlueStacks |

---

# 🚀 Главный проект

## Эрида · Kingdom Guard Assistant

**Десктопный ассистент для Windows, автоматизирующий рутинные действия в Kingdom Guard.**

Проект объединяет сразу несколько направлений:

```text
                    ЭРИДА
                       │
        ┌──────────────┼──────────────┐
        │              │              │
     Desktop       Automation      Android
        │              │              │
   AvaloniaUI       Scripts           ADB
        │              │              │
        └──────────────┼──────────────┘
                       │
                Computer Vision
                       │
                     YOLO
```

В проекте используются:

- .NET;
- AvaloniaUI;
- Android Debug Bridge;
- Computer Vision;
- YOLO;
- ONNX Runtime;
- DirectML;
- асинхронные очереди;
- управление несколькими Android-эмуляторами;
- сценарные движки;
- автоматическое распознавание состояния интерфейса.

Фарм, сбор наград, задания, магазин и другие повторяющиеся игровые действия объединены в одном приложении.

[![Project](https://img.shields.io/badge/Проект-Kingdom--Guard--Bot-6366F1?style=flat-square&logo=github&logoColor=white)](https://github.com/marksoft1993/Kingdom-Guard-Bot)
[![Website](https://img.shields.io/badge/Сайт-24erida.ru-0F766E?style=flat-square)](https://24erida.ru)

Публичный репозиторий содержит описание проекта и инструкцию по началу работы.

Исходный код основного приложения не публикуется.

---

# 🔬 Security Research

Мне особенно интересны проекты, находящиеся на пересечении разработки и информационной безопасности.

Например:

```text
Reverse Engineering
        +
Network Analysis
        +
Dynamic Instrumentation
        +
.NET Development
        ↓
Security Research Tools
```

Изучаю создание собственных инструментов для:

- анализа приложений;
- автоматизации исследований;
- обработки сетевых данных;
- визуализации результатов;
- анализа runtime-состояния;
- взаимодействия с Android;
- исследования клиент-серверной архитектуры.

---

# 🎯 Сейчас изучаю

```text
Advanced Reverse Engineering
        │
        ├── Native Code Analysis
        ├── Android Internals
        ├── IL2CPP
        ├── Runtime Instrumentation
        ├── Memory Analysis
        ├── Network Protocols
        └── Application Security
```

Также продолжаю развивать собственные инструменты на .NET для автоматизации анализа приложений.

---

# ⚖️ Responsible Security

Все исследования в области безопасности выполняются в рамках:

- собственных приложений и инфраструктуры;
- тестовых окружений;
- CTF;
- лабораторий;
- открытых исследовательских задач;
- систем, на исследование которых получено разрешение.

Цель — изучение архитектуры, развитие навыков анализа программного обеспечения и создание инструментов для defensive security и security research.

---

# 📫 Связаться

Открыт к обсуждению проектов в областях:

**Cybersecurity · Reverse Engineering · .NET · Automation · Computer Vision**

По вопросам **«Эриды»**, разработки или совместных проектов:

[![Telegram](https://img.shields.io/badge/Telegram-@Mark__Soft-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Mark_Soft)

---

<div align="center">

### MarkSoft

**Cybersecurity · Reverse Engineering · Development · Automation**

<sub>Исследую системы. Разрабатываю инструменты. Автоматизирую процессы.</sub>

</div>
