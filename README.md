# UW Issue Submission

**A quick form for underwriters to report cases where the AI document review got it wrong, so every miss becomes feedback for the vendor instead of a hallway complaint.**

[Live demo](https://piperintech.github.io/UW_Issues-/) · Built for SNAP Insurance Service LLC

---

## The problem

After SNAP rolled out automated document review with the vendor Inaza, underwriters were catching wrong PASS/FAIL results but had no consistent way to report them. Feedback got lost in email and chat, so the vendor couldn't see patterns.

## What it does

- Underwriter enters the policy number, document type and what went wrong, in under a minute
- Every submission is listed in **Submitted Cases**, so the team can see what's already been reported
- Entries feed the INAZA feedback tracking workflow (export → Excel workbook → vendor review)

## Stack

HTML, CSS, vanilla JavaScript · browser `localStorage` for submitted cases · GitHub Pages

## Why it matters

Turning scattered complaints into structured data meant we could go to the vendor with counts by issue type instead of anecdotes.

---

Built by **Manuela Gonzalez Piper** · Product & AI · [GitHub](https://github.com/piperintech)
