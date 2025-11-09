# 🟦 Boxy

**Boxy** is a lightweight web playground for creating, moving, resizing, and coloring boxes on an interactive HTML canvas.

Perfect for experimenting with layout ideas, visual planning, or just having fun drawing boxes.

---

## 🚀 Features

- ✏️ Add boxes to the canvas
- 🎨 Change their color using a color picker
- ↔️ Move and resize boxes freely
- 📏 See box dimensions in **millimeters (mm)**
- ❌ Delete selected boxes  
- 🧭 Minimal, zero-dependency interface

---

## 🧩 How It Works

Boxy uses a standard HTML5 `<canvas>` element with pure JavaScript for interactivity.

- Each box has:
  ```js
  { x, y, w, h, color }

	•	Canvas coordinates are in pixels, but sizes are also shown in millimeters, using:

1 px ≈ 0.2646 mm  (25.4 / 96)



⸻

🪄 Controls

Action	Description
🖱️ Click + drag	Move selected box
↘️ Drag small corner square	Resize selected box
➕ Add Box	Creates a new box
🎨 Color Picker	Change color of selected box
🗑️ Delete Selected	Remove current box
📐 Size display	Shown in top bar in mm


⸻

🧱 File Structure

boxy/
│
├── index.html        # Main HTML file (contains all JS and CSS)
├── README.md         # This file


⸻

💻 Run Locally
	1.	Save index.html to any folder.
	2.	Open it in your browser (double-click or drag to tab).
	3.	Start adding boxes!

No server needed — pure front-end fun.

⸻

🧠 Ideas for Expansion
	•	Save / load layouts (as JSON)
	•	Add text labels inside boxes
	•	Snap to grid option
	•	Export to image or SVG
	•	Align / distribute tools

⸻

⚡ License

Free to use, modify, and share.
Made with ❤️ for quick canvas prototyping.

---

Would you like me to add a simple **logo (SVG)** for “Boxy” — maybe a blue square with the word inside — so it looks nice in the README and as a favicon?