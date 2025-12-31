# QuitSmoke: Your Personalized Journey to a Smoke-Free Life

## Project Overview

**QuitSmoke** is a comprehensive, gamified web application designed to support individuals in their journey to quit smoking. It combines behavioral science principles with engaging interactive tools and tracking features to help users manage cravings, monitor progress, and build a healthier, smoke-free life.

The application is built as a modern Single Page Application (SPA) using a robust and scalable technology stack.

## Table of Contents

1.  [Features](#features)
2.  [Technology Stack](#technology-stack)
3.  [Installation and Setup](#installation-and-setup)
    *   [Prerequisites](#prerequisites)
    *   [Cloning the Repository](#cloning-the-repository)
    *   [Installing Dependencies](#installing-dependencies)
    *   [Running the Application](#running-the-application)
    *   [Building for Production](#building-for-production)
4.  [Project Structure](#project-structure)
5.  [License](#license)

## Features

QuitSmoke offers a variety of tools categorized to address different aspects of the quitting process:

### 📊 Progress Tracking & Motivation
*   **Quit Journey Statistics:** Tracks days smoke-free, estimated money saved, and health improvement percentage.
*   **Habits Tracker:** Allows users to monitor and log new, healthy habits.
*   **Mood Tracker:** Helps users identify emotional triggers and patterns.
*   **Sleep Tracker:** Monitors sleep quality, a crucial factor in managing stress and cravings.
*   **Stress Meter & Craving Predictor:** Tools to help users understand and anticipate high-risk moments.

### 🧠 Behavioral & Coping Tools
*   **Breathing Exercise:** Guided exercises for immediate stress and craving relief.
*   **Calming Sounds & Soundscape:** Customizable ambient soundscapes for relaxation.
*   **Quick Journal:** A simple tool for logging thoughts and feelings during cravings.
*   **Virtual Coach:** Provides motivational messages and personalized advice.
*   **Quit Plan Generator & Trigger Identifier:** Helps users formalize their quitting strategy and recognize personal triggers.

### 🎮 Gamification & Distraction
*   **Cigarette Tap Game:** A simple, engaging game to distract from immediate cravings.
*   **Memory Game, Puzzle Game, Reaction Game:** Quick, focused games to divert attention.
*   **Stress Ball:** A virtual interactive tool for managing physical tension.

## Technology Stack

The project is built using the following core technologies:

| Category | Technology | Description |
| :--- | :--- | :--- |
| **Frontend Framework** | React | A declarative, component-based JavaScript library for building user interfaces. |
| **Language** | TypeScript | A strongly typed superset of JavaScript that enhances code quality and maintainability. |
| **Build Tool** | Vite | A fast, modern build tool that provides an instant development server. |
| **Styling** | Tailwind CSS | A utility-first CSS framework for rapidly building custom designs. |
| **Component Library** | Radix UI / Shadcn/ui | Headless component primitives for high-quality, accessible UI components. |
| **State Management** | React Query (TanStack) | Used for data fetching, caching, and synchronization. |
| **Routing** | React Router DOM | Declarative routing for the Single Page Application. |
| **Package Manager** | pnpm | Fast, disk space efficient package manager. |

## Installation and Setup

Follow these steps to get a local copy of the project up and running on your machine.

### Prerequisites

You will need the following software installed on your system:

*   **Node.js** (version 18 or higher)
*   **pnpm** (Package Manager)

You can install `pnpm` globally using npm:
```bash
npm install -g pnpm
```

### Cloning the Repository

First, clone the repository to your local machine:

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd quit-smoking-app
```
*(Note: Replace `<YOUR_GITHUB_REPOSITORY_URL>` with the actual URL once you create the repository on GitHub.)*

### Installing Dependencies

Use `pnpm` to install all necessary project dependencies:

```bash
pnpm install
```

### Running the Application

To start the development server and view the application in your browser:

```bash
pnpm run dev
```

The application will typically be available at `http://localhost:5173` (or a similar port displayed in your terminal).

### Building for Production

To create an optimized, production-ready build of the application:

```bash
pnpm run build
```

The compiled files will be placed in the `dist/` directory. You can then serve these files using any static file server.

## Project Structure

The main application logic resides in the `src/` directory:

```
quit-smoking-app/
├── public/               # Static assets (favicon, images)
├── src/
│   ├── components/       # Reusable UI components (e.g., Button, Card)
│   │   └── ui/           # Shadcn/ui components
│   ├── hooks/            # Custom React hooks
│   ├── lib/              # Utility functions (e.g., utils.ts)
│   ├── pages/            # Main application views (e.g., Index.tsx, MoodTracker.tsx)
│   ├── App.tsx           # Main application component
│   ├── globals.css       # Global styles and Tailwind directives
│   └── main.tsx          # Entry point for the React application
├── index.html            # Main HTML file
├── package.json          # Project metadata and dependencies
├── tailwind.config.ts    # Tailwind CSS configuration
└── vite.config.ts        # Vite build tool configuration
```

## License

This project is licensed under the MIT License. See the LICENSE file for details.
*(Note: You will need to create a separate `LICENSE` file for your repository.)*

