[README.md](https://github.com/user-attachments/files/28613679/README.md)
# ⚖️ CivPro Finals Quiz

A self-contained multiple-choice quiz app for Law 125 (Civil Procedure) finals review. No internet connection required after loading — works entirely in the browser.

**Live site:** [herzeldrewrl.github.io/civprofinals](https://herzeldrewrl.github.io/civprofinals/)

---

## Coverage

577 questions across 20 sections:

| Section | Topic | Questions |
|---------|-------|-----------|
| Q | Judgments & Final Orders | 20 |
| R1 | Motion for New Trial / Reconsideration | 20 |
| R2 | Appeals (Rules 40–45) | 100 |
| R3 | Relief from Judgments | 20 |
| R4 | Annulment of Judgments | 20 |
| R5 | Execution (Rule 39) | 70 |
| T1 | Preliminary Attachment | 30 |
| T2 | Preliminary Injunction | 30 |
| T3 | Receivership | 15 |
| T4 | Replevin | 20 |
| T5 | Support Pendente Lite | 15 |
| U1 | Interpleader | 20 |
| U2 | Declaratory Relief | 20 |
| U3 | Certiorari, Prohibition & Mandamus | 50 |
| U4 | Quo Warranto | 20 |
| U5 | Expropriation | 15 |
| U6 | Foreclosure of Real Estate Mortgage | 15 |
| U7 | Partition | 17 |
| U8 | Forcible Entry & Unlawful Detainer | 40 |
| U9 | Contempt | 20 |

> U8 questions are based on the **Rules on Expedited Procedures in the First Level Courts (A.M. No. 08-8-7-SC)** which supersedes Rule 70 where they conflict.

---

## Features

- **Section picker** — choose any combination of sections to quiz on
- **Flexible quiz size** — 5, 10, 20, 30, 50, or all questions per session
- **Randomized questions** — different order every time
- **Unseen questions first** — tracks which questions you've already seen and prioritizes new ones; resets automatically once all questions are covered
- **Instant feedback** — shows correct answer and explanation after each question
- **Review mode** — replay only the questions you got wrong
- **Score history** — saves your scores across sessions with average calculation
- **Works offline** — single HTML file, no server needed

---

## How to Use

1. Open the quiz
2. Select the sections you want to review
3. Choose how many questions (5 / 10 / 20 / 30 / 50 / All)
4. Click **Start Quiz**
5. After finishing, review wrong answers or start a new quiz

---

## Tech

Single-file HTML/CSS/JS app. No frameworks, no dependencies, no build step. Score history and seen-question tracking use `localStorage`.

---

*Built for personal bar exam review purposes.*
