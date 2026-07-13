Github Pages:
https://rafaelqcc.github.io/ascii-generator-fork/

# ASCII Generator

Single-file ASCII art generator. Type text, pick a font, export as PNG, SVG, or TXT. Fully offline — no install, no server, no internet required.

# Local Server Requirements (Optional)

The local server is optional and only needed if your browser has limitations when opening local HTML files or does not allow some JavaScript features to run from "file://".

# Install Node.js

# Windows

Download and install Node.js from the official website:

```
https://nodejs.org/
```

After installation, verify:

```
node --version
```

# Linux

Debian/Ubuntu:

```
sudo apt install nodejs
```

Arch Linux:

```
sudo pacman -S nodejs
```

Termux (Android)

Install Node.js with:

```bash
pkg update
pkg install nodejs
```

Verify:

```bash
node --version
```

Start the local server

Inside the project folder:

```
node server.js
```

Then open:

```
http://127.0.0.1:8080
```

## Quick Start

**Option 1 — Download directly**
1. Download [`index.html`](https://raw.githubusercontent.com/rafaelqcc/ascii-generator/main/index.html)
2. Open it in your browser

**Option 2 — Clone the repo**
```bash
git clone https://github.com/rafaelqcc/ascii-generator.git
cd ascii-generator
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Or start the local server:
```bash
node server.js
```

That's it. No `npm install`, no dependencies, no build step.

## Features

- **27 fonts** — all embedded offline (Banner3-D, Star Wars, Graffiti, Gothic, Isometric1, and more)
- **Multiline support** — each line in the textarea renders as its own block
- **Live preview** — updates as you type
- **Light / dark mode** toggle
- **Export options**
  - Copy as text
  - Copy or save as PNG (with padding, 1×/2×/3× resolution, custom colors)
  - Copy or save as SVG (infinitely scalable)
  - Save as TXT
- **Transparent PNG background** option
- **Preview color pickers** — background and text color for the live view
- **PNG color pickers** — independent background and text color for exports

## Fonts Included

| Style | Fonts |
|---|---|
| Block / Banner | Banner3-D, Banner3, Block, Colossal, Chunky |
| 3D | 3D-ASCII, Isometric1, Larry 3D |
| Shadow | ANSI Shadow, Shadow |
| Grunge | Graffiti, Bloody, Gothic |
| Classic | Standard, Big, Roman, Slant, Epic |
| Fun | Star Wars, Varsity, Puffy, Bubble-adjacent |
| Compact | Calvin S, Ogre, Cyberlarge, Rectangles |
| Motion | Speed, Doom |
