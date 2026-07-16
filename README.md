# Agentic Integrate — Roadmap Canvas

An interactive, pan/zoom timeline of the Agentic Integrate program: foundations below the line, capabilities above, with a phase-header narrative running left to right (summarize → understand risk → understand everything → change → build → access anywhere).

## Viewing

Open `agentic-integrate-ceo-canvas.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8232
# then open http://localhost:8232/agentic-integrate-ceo-canvas.html
```

## Controls

- **Drag** to pan · **⌘/Ctrl + scroll** (or pinch) to zoom · **double-click** to zoom in
- **Click a node** to focus its connections
- Bottom nav jumps between eras (Overview / Shipped / In Flight / The Agent / Horizon)
- Arrow keys pan · `+` / `-` zoom · `0` fit · `1`–`5` eras

## Editing

Everything is a single self-contained HTML file. Nodes are `<div class="node ...">`
elements positioned with inline `left`/`top`; connections live in the `EDGES` array
in the inline `<script>`.
