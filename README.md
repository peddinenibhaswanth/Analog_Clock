# 🕒 Analog Clock – Pure JavaScript

A lightweight and responsive analog clock built using only **HTML**, **CSS**, and **JavaScript**. It dynamically displays the current time by rotating hour, minute, and second hands in real time.

---

## 📸 Preview

![Analog Clock Preview](./clock.png)  
*(Make sure `clock.png` is present in your project directory. It acts as the clock face.)*

---

## 📁 Project Structure


├── index.html # Main HTML layout
├── index.css # Clock styling and positioning
├── index.js # Real-time clock logic using JS
└── clock.png # Clock face image used as background


---

## 🚀 Features

- ✅ Built using **pure HTML, CSS, and JavaScript**
- 🕰️ Accurate real-time clock functionality
- 💻 Fully responsive using `vw` units
- 🎨 Clean and minimal UI
- 📐 Accurate rotation for all three clock hands

---

## 🔧 How It Works

### 🧠 JavaScript Logic

- `setInterval()` is called every second to update the time.
- `Date()` object fetches the **current hour, minute, and second**.
- Rotations are calculated as:
  - **Hour hand** → `30 * hours + minutes / 2`
  - **Minute hand** → `6 * minutes`
  - **Second hand** → `6 * seconds`
- These values are applied using `style.transform = rotate(...)`.

---

## 💻 How to Run the Project

1. Download or clone this repository.
2. Make sure all these files exist in the same directory:
   - `index.html`
   - `index.css`
   - `index.js`
   - `clock.png`
3. Open `index.html` in any modern web browser.
4. Watch the clock tick in real-time!

---

## 💡 Customization Ideas

- 🎵 Add ticking sound with JavaScript audio
- ⏰ Add digital time display below the analog clock
- 🌗 Add Dark/Light theme toggle
- 🖼️ Change the background or hand designs using images or CSS

---

> 💬 If you like this project, don’t forget to give it a ⭐ on GitHub!

