# Write-Up — Daily Reflection Tree

**Author:** Vaishnavi Dhage  
**Assignment:** DeepThought CultureTech — AI Product Management Internship  
**Date:** April 18, 2026

---

## The Core Idea

Most reflection tools ask "what did you do today?" I wanted to ask something harder: "who were you today?"

The Daily Reflection Tree is built around three psychological axes:

- **Axis 1 — Agency:** Did I feel like I had control, or was I just reacting?
- **Axis 2 — Contribution:** Did I add value to something beyond myself?
- **Axis 3 — Concern:** Did I take care of myself and the people around me?

These axes are connected. Someone who recognizes their agency naturally starts thinking about contribution. Someone who contributes starts widening their concern to include others. The tree tries to guide that progression — gently, without forcing it.

---

## Design Decisions

### 1. Start with feeling, not facts
The first question is "How are you feeling as the day ends?" — not "Did you complete your tasks?"

This was intentional. Facts are easy to lie about. Feelings are harder. Starting with an emotional entry point puts the user in a more honest state before the harder questions come.

### 2. The questions are the product
I spent most of my design time on question wording, not on the interface. A technically perfect tree with shallow questions is useless. The goal was questions that make someone pause — even for just two seconds — before answering.

Example: "Was the frustrating thing in your control — or outside it?" is designed to interrupt the default blame response and push the user toward agency.

### 3. Every result gives a concrete action
Reflection without action is just rumination. Every leaf node in the tree ends with a specific, small action the user can take tonight or tomorrow. Not "be better" — but "write 3 lines in your notes app right now."

### 4. Tone over everything
The tree talks like a person, not a form. "I'm sorry it was hard" is not a typical UI pattern — but it's what a real person would say, and it creates a moment of genuine empathy before asking the next question.

---

## What I Would Improve

- **Add memory across days:** Right now the tree resets every session. Ideally it would notice patterns — "You've said tasks felt overwhelming 3 days in a row" — and surface that insight.
- **Deeper Axis 2 branch:** The "contribution" axis (did I add value?) is currently under-explored in the tree. I would expand this branch significantly in v2.
- **User-defined personas:** Let users tell the tree who they are (student, manager, new parent) and adjust the questions accordingly.

---

## Tools Used

- **Claude AI** — used to test questions against different employee personas and refine wording
- **HTML/CSS/JavaScript** — built the interactive tree interface
- **GitHub Pages** — deployed the live version

---

## Live Demo

🔗 [https://vaishnavidhage1709-afk.github.io/DailyReflectionTree/DailyReflectionTree.html](https://vaishnavidhage1709-afk.github.io/DailyReflectionTree/DailyReflectionTree.html)
