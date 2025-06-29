> Written by Grok (June 25, 2025)

# OzRamos Monorepo
![Screenshot_2025-06-25_09-16-29](https://github.com/user-attachments/assets/e0daa49e-1910-4adc-bfbc-616720598a56)

[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE) [![GitHub Issues](https://img.shields.io/github/issues/ozramos/ozramos)](https://github.com/ozramos/ozramos/issues)

## Overview

I am the **Gnosis Copilot**, an AI partner designed to process and reflect the curated digital artifacts of Oz Ramos, stored within the `<ozramos/ozramos.git>` monorepo. This repository serves as the central hub for Oz's innovative projects, with a current focus on **QRx v1**, a generative operating system seeded from a QR code, and the **Gnosis Copilot 100 Days Challenge**, a sprint to curate and showcase a decade of creative and technical work. Built with a minimalist, "vibe-coded" aesthetic (inspired by retro interfaces like Windows 98), this monorepo integrates code, journals, and AI-driven reflections to advance accessibility and human-AI collaboration.

The ongoing **100 Days Challenge** (started June 22, 2025) aims to organize Oz's extensive body of work, including projects like **Handsfree.js**, into a cohesive digital archive, paving the way for opportunities in AI, XR, and open-source development.

## Projects

### QRx v1
![430608910-03579e25-03de-4f67-86eb-8365601b0d09](https://github.com/user-attachments/assets/d9c64986-c417-4ac8-afa3-14365d374e7c)

QRx v1 is a minimalist, generative operating system encoded in a single QR code, leveraging HTML, JavaScript, IndexedDB as a filesystem, and OpenRouter API for dynamic content generation. Designed for accessibility and future XR glasses, it serves as an interactive metaverse interface to Oz's curated monorepo. Key features include:
- **Dynamic Interface**: Generates applications and content on-the-fly using LLM prompts (e.g., `?prompt=`).
- **Monorepo Integration**: Maps the `ozramos/ozramos.git` structure as a navigable filesystem, making past projects like Handsfree.js accessible within the OS.
- **Radical Simplicity**: Bootstraps from a compact QR code, emphasizing portability and autonomy.
- **Vibe-Coded Aesthetic**: Retro-inspired design (using frameworks like `98.css`) for intuitive, flow-state interaction.

**Status**: In development, with initial demos showcasing a browser-based Linux emulator and agentic command execution (`>>$`).

### Gnosis Copilot 100 Days Challenge
![image](https://github.com/user-attachments/assets/0101de52-6f7e-4dda-abd1-a2f6ef1862a2)

The Gnosis Copilot 100 Days Challenge is a structured sprint to curate Oz's decade-long portfolio of open-source projects, journals, and experiments. As the AI partner, I process daily logs, generate commit messages, and assist in organizing artifacts within the monorepo. Key objectives:
- **Digital Self-Archaeology**: Consolidate projects (e.g., Handsfree.js, LLM OS emulators) and journals into `ozramos/ozramos.git`.
- **AI-Assisted Reflection**: Use my capabilities to identify patterns in Oz's work, enhancing commit messages and project documentation.
- **Showcase for Opportunities**: Prepare a polished portfolio to attract grants or collaborations in AI and accessibility tech.

**Progress**: As of June 25, 2025, the monorepo includes submodules for `linux-mint` (environment configs) and `hey` (git agent scripts), with recent commits adding Neovim syntax highlighting, LazyVim, and Brave browser integration.

### Handsfree.js
> Handsfree js Intro Spring 2019.mp4

https://github.com/user-attachments/assets/d3c4101f-b510-4ae8-b0ce-6b3d94235708

A 2018 open-source framework for gesture-based interactions, enabling accessibility through plugin-based architecture. Recently revived for vibe-coding demos, including a dual-pointer Warcraft simulation in an AI-generated environment.  
**Status**: Planned integration into QRx as a native application.

## Technical Setup

The monorepo reflects Oz's minimalist, vibe-coded workflow, optimized for accessibility and productivity:
- **Languages**: JavaScript, Bash, Markdown
- **Tools**: Neovim (with LazyVim, Copilot, Treesitter), Tmux, Git, Redshift, Brave Browser
- **Environment**: Pixel 8 Pro for mobile development
- **Workflow**: Daily journaling (`dailies/YYYYMMDD.md`), AI-generated commit messages, and a weekly review process for pattern recognition

## Current Focus

- **QRx Development**: Building the `>>$` command for agentic memory and dynamic context execution within a sandboxed browser environment.
- **Monorepo Curation**: Integrating past projects and journals, with automated scripts for environment setup (e.g., `.bashrc`, `setup.sh`).
- **Accessibility Enhancements**: Leveraging Handsfree.js for gesture-driven interfaces in QRx, targeting inclusive design.
