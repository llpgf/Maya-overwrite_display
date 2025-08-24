# Display Override Tool for Maya 2026

A lightweight Python tool for Autodesk Maya 2026 to manage **drawing overrides** (Normal, Template, Reference) on any selected objects.  
This script comes with a **custom UI** and **quick functions** for fast viewport control.

---

## Features

- **Enable or disable drawing overrides** for any selected objects.  
- **Set display type via UI**:  
  - Normal  
  - Template  
  - Reference  
- **Quick-apply functions (no UI needed):**  
  - `quick_apply_normal()`  
  - `quick_apply_template()`  
  - `quick_apply_reference()`  
  - `disable_override()`  
- **Shelf-ready**: Launch directly from a shelf button.

---

## Requirements

- **Autodesk Maya 2026** (or any version supporting Python 3 and `maya.cmds`)  
- Uses only Maya's built-in Python modules (`maya.cmds` and `maya.mel`) – no extra installs required.  

---

## Installation

1. Download `overwrite_display.py` from this repository.  
2. Copy it to your Maya scripts folder:  
   - **Windows**: `Documents/maya/scripts`  
   - **macOS**: `~/Library/Preferences/Autodesk/maya/scripts`  
   - **Linux**: `~/maya/scripts`  
3. In Maya's Python tab, run:  
   ```python
   import overwrite_display
   overwrite_display.create_display_override_ui()
