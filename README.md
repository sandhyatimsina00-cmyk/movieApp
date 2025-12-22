## 🎬 Movie App (React)

A modern movie browsing React application built using component-based architecture and custom hooks.
The project follows a professional Git workflow, includes CI/CD with GitHub Actions, and is deployed to Vercel.

## Project Information

This Movie App allows users to search for movies, view details, and interact with movie data through a clean and responsive UI.
It is designed as a single-page application (SPA) with scalability and maintainability in mind.

## 🚀 Tech Stack

React

Vite

JavaScript (ES6+)

CSS

Git & GitHub

GitHub Actions (CI/CD)

Vercel (Production Deployment)

## ✨ Key Features

Movie search functionality

Reusable React components

Custom React hooks for logic separation

Local storage state management

Clean folder and component structure

Automated deployment via CI/CD

## ⚙️ Getting Started

## Installation

git clone https://github.com/your-username/movieApp.git
cd movieApp
npm install
npm run dev

##🌍 Deployment

- Automatically deployed on Vercel

- Deployment triggered when changes are merged into the dev branch via GitHub Actions

## Development Workflow Guide

### Branch Type

- **main**

  - Production-ready code only

- **develop**

  - Active development branch

- **feature/\***

  - Used for new features
  - Created from `develop`
  - Merged back into `develop`

- **fix/\***

  - Used for non-urgent bug fixes
  - Created from `develop`
  - Merged back into `develop`

- **hotfix/\***

  - Used for urgent production bugs
  - Created from `main`
  - Merged into both `main` and `develop`

- **release/\***
  - Used to prepare a new release
  - Created from `develop`
  - Merged into `main` and `develop`

## 📦 Release Notes

Release notes are maintained in this README under the following format:

### v1.0.0 – YYYY-MM-DD

- v1 --> release version
- 0 --> initial feature set
- 0 --> no patch yet

#### ✨ Features

- Core movie browsing functionality

- Component-based React architecture

- Custom hooks for state and logic

- Local storage integration

#### 🐛 Bug Fixes

- N/A (initial release)

#### 🔧 Improvements

- Clean and scalable folder structure

- CI/CD pipeline integration

- Optimized deployment workflow
