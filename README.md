# 🎭 Fake Results Portal (Prank Page)

A prank web page styled as a college exam-results portal. Enter any hall ticket number and it shows a convincing – but completely **randomly generated** – marks sheet, then reveals that it's a prank.

> ⚠️ **For educational and fun purposes only.** It does not connect to any real results system and every mark shown is random.

## ✨ Features

- Results-portal style page with a hall-ticket input form
- 3-second "loading" animation before results appear
- Random marks (65–95) for 4 subjects: Engineering Mathematics, Applied Physics, Programming for Problem Solving, English
- Grade for each subject (O, A+, A, B+, B), total marks and percentage
- A prank message slides in 10 seconds after the results appear
- Entered hall-ticket numbers are kept in the browser's `localStorage` (on the user's own device only)

## 🛠️ Tech Stack

- HTML5, CSS3
- Vanilla JavaScript

## 📁 Project Structure

```
fake-results-portal/
├── fake_results_portal.html   # The full page (markup, styles, logic)
└── fake_results_portal.zip    # Zipped copy of the page
```

## 🚀 Run Locally

```bash
git clone https://github.com/shivamani-code/fake-results-portal.git
cd fake-results-portal
```

Open `fake_results_portal.html` in any browser.
