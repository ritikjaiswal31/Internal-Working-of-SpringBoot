# Internal-Working-of-SpringBoot

A deep-dive project exploring and demonstrating the internal workings of the Spring Boot framework — including how components are wired, how auto-configuration operates, how beans are managed, and how the startup process unfolds.

---

## 🧩 Overview

This repository provides **educational code samples** and explanations for how **Spring Boot** internally manages:

- Auto-configuration discovery and application  
- Bean instantiation and dependency injection  
- ApplicationContext lifecycle  
- Conditional configuration and property resolution  
- The startup sequence (`SpringApplication.run(...)`)  
- Custom hooks such as `ApplicationRunner` and `CommandLineRunner`

It’s designed for developers who want to *understand* Spring Boot internals rather than just use them.

---

## 🎯 Motivation

Spring Boot simplifies development by hiding complex configurations — but understanding what happens under the hood helps you:

- Debug and optimize applications more effectively  
- Customize framework behavior confidently  
- Gain insight into Spring’s dependency injection and lifecycle  
- Understand startup performance and context initialization  

This project walks through core internals, showing what actually happens behind the annotations.

---

## ⚙️ Architecture & Components

This project explores these fundamental internal mechanisms:

- **Auto-Configuration Modules** — how Spring Boot selects and applies configurations  
- **SpringFactories Mechanism** (`spring.factories`) — how auto-configurers are discovered  
- **BeanPostProcessor / BeanFactoryPostProcessor** — customization hooks for beans  
- **ApplicationContext Lifecycle** — creation, refresh, and shutdown phases  
- **Conditional Annotations** (`@Conditional`, `@ConditionalOnProperty`, etc.)  
- **Profiles and Environment Abstraction**  
- **Startup Listeners and Runners** — extending application behavior post-startup  

> You can use a debugger or logs to follow how Spring Boot loads, configures, and runs your app.

---

## 🚀 Getting Started

### Prerequisites

- **Java JDK 11+**  
- **Maven** or another build tool  
- **IDE** (IntelliJ IDEA, Eclipse, or VS Code)  
- Basic understanding of **Spring Framework**

---

### Cloning & Setup

```bash
git clone https://github.com/ritikjaiswal31/Internal-Working-of-SpringBoot.git
cd Internal-Working-of-SpringBoot
