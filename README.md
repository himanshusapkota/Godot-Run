# Godot-Run

A simple endless runner game built with the [Godot Engine](https://godotengine.org/).

## About

This project is a small 2D endless runner ("EndlessRunner") made in Godot. It includes a web export, so the game can be played directly in a browser without installing anything.

## Project Structure

```
Godot-Run/
├── addons/
│   └── godot_super-wakatime/   # Wakatime plugin for tracking coding time in the editor
├── scenes/                     # Godot scene files
├── icon.svg                    # Project icon
├── main.tscn                   # Main scene
├── project.godot                # Godot project configuration
├── export_presets.cfg           # Export settings (e.g. Web/HTML5)
└── EndlessRunner.*               # Exported HTML5/WebAssembly build
    (.html, .js, .wasm, .pck, .png, worklet files)
```

## Requirements

- [Godot Engine](https://godotengine.org/download) (to open and edit the project)
- A modern web browser (to play the exported HTML5 build)

## Getting Started

### Play in the browser

Open `EndlessRunner.html` in a web browser to play the pre-exported build.

### Run from source

1. Install [Godot Engine](https://godotengine.org/download).
2. Clone this repository:
   ```
   git clone https://github.com/himanshusapkota/Godot-Run.git
   ```
3. Open Godot, click **Import**, and select the `project.godot` file.
4. Press **Run** (F5) to play the game in the editor.

