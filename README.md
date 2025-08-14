# 🌍 DDOSn't Matter - Global DDoS Attack Visualizer

> Real-time 3D visualization of global DDoS attacks on an interactive Earth globe

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js_15-000000?logo=next.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?logo=react&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?logo=three.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

## 🚀 Overview

DDOSn't Matter is a sophisticated real-time web application that visualizes global DDoS attacks on a stunning 3D Earth globe. Built as a portfolio project, it demonstrates advanced full-stack development practices, modern visualization techniques, and clean architecture principles.

*🚧 This project is currently in active development*

## ✨ Features

### 🌐 Interactive 3D Visualization
- **Photorealistic Earth Globe**: Three.js-powered 3D Earth with realistic textures and lighting
- **Animated Attack Trajectories**: Real-time arcing animations from attack source to target
- **Interactive Controls**: Zoom, rotate, and explore attacks from any angle
- **Dynamic Hotspots**: Pulsating markers indicating active attack zones

### 📊 Real-time Dashboard
- **Live Attack Feed**: WebSocket-powered real-time attack data streaming
- **Advanced Filtering**: Filter by country, attack type, severity, and time range
- **Analytics & KPIs**: Attack frequency, top targets, geographical distribution
- **Historical Trends**: Time-series charts showing attack patterns over time

### 🏗️ Enterprise Architecture
- **Clean Architecture**: Domain-driven design with strict separation of concerns
- **SOLID Principles**: Maintainable, testable, and extensible codebase
- **Dependency Injection**: Loosely coupled components for better testing
- **Event-Driven Design**: Scalable real-time data processing

## 🛠️ Technical Stack

### Frontend
- **Next.js 15** - React framework with App Router and Turbopack
- **React 19** - Latest React with concurrent features
- **TypeScript 5** - Type-safe development
- **Tailwind CSS 4** - Utility-first styling framework
- **Three.js + React Three Fiber** - 3D rendering and animations
- **React Three Drei** - Helper components for R3F
- **Socket.IO Client** - Real-time WebSocket communication
- **Zustand** - Lightweight state management
- **TanStack Query** - Server state management and caching
- **Recharts** - Interactive data visualization charts
- **Lucide React** - Beautiful icon library

### Backend
- **NestJS** - Enterprise-grade Node.js framework with dependency injection
- **TypeScript 5** - End-to-end type safety
- **Clean Architecture** - Domain/Application/Infrastructure layers
- **Socket.IO** - Real-time WebSocket server
- **Prisma ORM** - Type-safe database access with PostgreSQL
- **PostgreSQL** - Primary database for attack data
- **Redis** - Caching and WebSocket session storage
- **Passport + JWT** - Authentication and authorization
- **Swagger** - Auto-generated API documentation
- **Class Validator** - DTO validation and transformation

### DevOps & Infrastructure
- **Docker & Docker Compose** - Containerized development environment
- **TypeScript ESLint** - Advanced linting with TypeScript support
- **Prettier** - Code formatting and style consistency
- **Jest + Supertest** - Unit and integration testing
- **SWC** - Fast TypeScript/JavaScript compilation
- **ts-jest** - TypeScript support for Jest testing

### External APIs
- **AbuseIPDB** - Real threat intelligence data
- **VirusTotal** - IP reputation checking
- **MaxMind GeoIP** - Geographic location data

## 👨‍💻 Author

**Nemo Kardassevitch**
- GitHub: [@nemokardassevitch](https://github.com/nkardas)
- LinkedIn: [Nemo Kardassevitch](https://linkedin.com/in/nemokardassevitch)

---

⭐ **Star this repository if you found it helpful!** ⭐