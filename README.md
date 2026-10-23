# ROS 2 Interface Spec Builder

A lightweight, browser-based tool for creating and documenting ROS 2 interface specifications, tracking design decisions, and exploring safety concepts.

**[Try it online](https://jlorenz-eng.github.io/ros2-interface-spec-builder/)**

## Features

- **Interface specifications:** Define ROS 2 topics, services, and actions, including fields, data types, and enums.
- **Review board:** Track open questions, design decisions, and responsibilities.
- **Safety concepts:** Define hazards, safety levels, and escalation rules with an interactive simulator.
- **Live preview:** See the generated documentation while editing.
- **Export:** Generate PDF and Markdown documents or save entire projects as JSON.
- **Import:** Load existing projects or merge selected parts of multiple projects.
- **Local storage:** No backend or installation required.

## Usage

Open the [web app](https://jlorenz-eng.github.io/ros2-interface-spec-builder/) or download `index.html` and open it in your browser.

Changes are automatically saved in your browser. Export your project as JSON to back it up or continue working on another device.

## Notes

This is an experimental tool created with AI assistance for personal use in ROS 2 development. It is provided as-is and may contain bugs.

The safety simulator is intended for conceptual exploration and does not replace formal safety analysis or validation.

## License

MIT
