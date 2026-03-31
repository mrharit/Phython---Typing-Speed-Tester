# ⌨️ Typing Speed Tester
### Mini Project 3 (Python)

---

## 📌 Project Overview

The **Typing Speed Tester** is a command-line Python application that measures a user's typing speed and accuracy.

The program displays a random sentence, tracks how long the user takes to type it, calculates **Words Per Minute (WPM)**, and determines **typing accuracy** using character-by-character comparison.

This project is ideal for practicing **Python fundamentals**, working with **time measurement**, and improving understanding of **string comparison logic**.

---

## 🎯 Objectives

- Measure typing speed in **Words Per Minute (WPM)**
- Calculate typing **accuracy percentage**
- Practice Python modules such as `time` and `random`
- Build a practical command-line utility

---

## 🛠️ Technologies Used

- **Python**
- Built-in modules:
  - `time`
  - `random`

No external libraries are required.

---

## ⚙️ How It Works

1. A random sentence is selected from a predefined list.
2. The user is shown the sentence and prompted to begin.
3. A timer starts when the user begins typing.
4. The timer stops when the user submits their input.
5. The program calculates:
   - **Time taken** (seconds)
   - **Words per minute (WPM)**
   - **Typing accuracy (%)**

---

## 📊 Calculation Logic

### 🧮 Words Per Minute (WPM)

Typing speed uses the standard WPM formula:

``

## 📊 Calculation Logic

### Words Per Minute (WPM)
``
WPM = Total Words Typed / Time Taken (in minutes)

In this script:
- Word count is derived from the displayed test sentence.
- Time is measured with Python’s `time.time()` (start → end).
- Result is shown to two decimal places.

---

### 🎯 Typing Accuracy (%)

Accuracy is computed by comparing each typed character with the corresponding character in the original sentence:


Accuracy (%) = (Correct Characters / Total Characters) × 100

- Only correctly matched characters are counted.
- Extra, missing, or incorrect characters reduce the score.
- Provides a realistic measure of precision.

---

## ▶️ How to Run

1. Ensure Python is installed.
2. Save the script as `typing_speed_tester.py`.
3. Open a terminal in the same directory.
4. Run:

```bash
python typing_speed_tester.py

Follow the on‑screen instructions and start typing!

🧪 Example Output
Type the following sentence as fast as you can:
The quick brown fox jumps over the lazy dog.
Press Enter when you are ready...

Start typing:
The quick brown fox jumps over the lazy dog.

Results:
Time taken: 11.82 seconds
Words typed: 9
Typing speed: 45.70 words per minute
Accuracy: 97.78%


✅ Features

Random sentence selection
Real-time typing speed calculation (WPM)
Character-level accuracy measurement
Simple, beginner-friendly CLI
No external dependencies


🔮 Future Improvements

Add multiple difficulty levels (easy/medium/hard)
Support multiple rounds and average/best scores
Show mistake count and highlight differences
Configurable sentence lists (from a file)
GUI version with Tkinter or PyQt


📁 Project Structure (suggested)
typing-speed-tester/
├─ typing_speed_tester.py
└─ README.md


👤 Author
Aakash Harit
Python Mini Projects | Command-Line Applications

📄 License
This project is intended for educational and learning purposes.

Want me to also generate a **concise repo description**, add **badges**, or create a **requirements-free GitHub Actions workflow** to auto‑test formatting?
