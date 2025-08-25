## Overview

This text editor is implemented using Racket's `2htdp/universe` and `2htdp/image` libraries. It features a minimal graphical interface and supports basic editing operations, font size adjustments, a menu, and a search mode.

---

### Features

- **Modes:**
  - `EDIT`  — standard editing mode.
  - `MENU`  — menu overlay for user instructions.
  - `SEARCH` — search overlay for finding text.

- **Key Bindings:**
  - `ESC` : Toggle menu.
  - `F1` : Decrease font size.
  - `F2` : Increase font size.
  - `F3` : Toggle search.
  - `HOME` : Move cursor to start of line or document.
  - `END` : Move cursor to end of line or document.
  - Arrow keys: Move cursor.
  - `Backspace`: Delete character to the left of the cursor (supports joining lines).
  - `Enter`: Insert a new line.
