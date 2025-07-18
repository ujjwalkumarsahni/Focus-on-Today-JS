# FocusOnToday 🧘‍♂️🗓️

**FocusOnToday** is a minimalistic and interactive daily goal tracker built with HTML, CSS, and JavaScript. It helps users stay productive by setting and completing three daily goals, visualized with a progress bar and motivational quotes.

## 🚀 Live Demo

🔗 [View Live Site](https://focus-on-today-ujjwal.netlify.app/)

## ✨ Features

* ✅ Add up to **three goals** per day
* 📌 Save goals and completion status in `localStorage`
* 🎯 Progress bar that updates as you complete tasks
* 💬 Dynamic motivational quotes based on your progress
* ⚠️ Error prompt when trying to mark goals before setting them

---

## 📁 File Structure

```
FocusOnToday/
│
├── index.html         # Main HTML layout
├── style.css          # Styling for the app (not included in your input)
├── script.js          # JavaScript logic
├── image/
│   ├── Sun.svg        # Icon used in header
│   └── Group 1.svg    # Custom checkmark icon
└── README.md          # Project documentation
```

---

## 🧠 How It Works

* Each goal is linked to an input field (`first`, `second`, `third`) and a custom checkbox.
* When all goals are filled, clicking the checkbox toggles its completed state and updates:

  * Progress bar width
  * Completion count (`X/3 Completed`)
  * Motivational quote from a predefined list
* All data is **persisted** using `localStorage`.

---

## 🔧 Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript
* Google Fonts (Poppins)

---

## 🚀 Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/FocusOnToday.git
   ```

2. **Open in browser:**

   You can directly open `index.html` in any modern browser.

3. **Or host locally with Live Server (VS Code extension recommended):**

   * Right-click `index.html` → "Open with Live Server"

---

## 📌 TODO / Improvements

* [ ] Responsive styling for mobile screens
* [ ] Add dark mode toggle
* [ ] Allow user to set more than 3 goals
* [ ] Add animation to check/uncheck events
* [ ] Store history of completed goals

---

## 👨‍💻 Author

**Name:** *Ujjwal Kumar*  
**Email:** ujjwalkumar0514@gmail.com  
**GitHub:** [github.com/ujjwalkumarsahni](https://github.com/ujjwalkumarsahni)  
**LinkedIn:** [linkedin.com/in/ujjwalkumarsahni](https://linkedin.com/in/ujjwalkumarsahni)
