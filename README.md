# Volt Programming Language Website

The official static website for **Volt**, a strictly typed, schematic-based programming language. This repository houses the frontend architecture that outlines the language philosophy, core syntax, and sample circuits.

🌐 **Live Site:** https://ryankkhalil19.github.io/volt-lang-site/
⚙️ **Interpreter Source Code:** https://github.com/ryankkhalil19/volt-interpreter

## What is Volt?
Volt replaces abstract control flow with physical hardware schematics. It forces developers to manage memory and execution paths explicitly through continuous traces. Designed with an electrical engineering philosophy, Volt ensures memory safety by physically requiring all data to be routed to a terminal Ground (`_|_`) component.

If a trace is left open, the compiler instantly shorts out and fails. There is no garbage collection. There are no hidden memory allocations. Every byte is accounted for visually.

## Repository Contents
This is a lightweight, strictly static frontend repository requiring no build tools or backend servers.
* `index.html`: The core landing page containing the language documentation.
* `style.css`: A custom, dark-theme stylesheet mimicking low-level terminal environments.
* `README.md`: Repository documentation.

## Local Development
To run this website locally on your machine, no dependencies are required.
1. Clone the repository:
   ```bash
   git clone https://github.com/ryankkhalil19/volt-lang-site.git
   ```
