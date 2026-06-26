# 🎯 Phishing Awareness Training — Case File #1

**CodeAlpha Cyber Security Internship — Task 2**

> An interactive, self-contained training module that teaches people to spot phishing the way an investigator reads evidence — built as a single HTML file with **zero dependencies**, ready to open in any browser or host instantly on GitHub Pages.

![Type](https://img.shields.io/badge/type-Interactive%20HTML%20Module-blue)
![Dependencies](https://img.shields.io/badge/dependencies-none-success)
![Status](https://img.shields.io/badge/status-Completed-success)

---

## 🖼️ Preview

| Hero / Briefing | Spot-the-Phish Evidence Cards | Field Test Quiz |
|---|---|---|
| ![Hero](screenshots/01_hero.png) | ![Evidence](screenshots/02_spot_the_phish.png) | ![Quiz](screenshots/03_field_test_quiz.png) |

---

## 📌 Task Brief (from CodeAlpha)

> Create a presentation or online module focused on phishing attacks. Explain how to recognize phishing emails and fake websites, educate about social engineering tactics, provide best practices, and include real-world examples and interactive quizzes.

This project delivers it as a **live, interactive web module** instead of a static slide deck — every requirement in the brief is implemented as something the learner *does*, not just reads.

---

## ✨ Why an interactive module instead of a slide deck

| Requirement from brief | How this module delivers it |
|---|---|
| Recognize phishing emails & fake sites | **4 "Exhibit" email cards** styled like detective case-file evidence — read first, then reveal annotated red flags one by one |
| Social engineering tactics | A **"Playbook"** section breaking attacks into 4 psychological levers: Urgency, Authority, Scarcity/Reward, Trust Transfer |
| Best practices | A **5-item Field Manual** checklist of concrete habits (check the domain, verify out-of-band, never enter credentials from a link, etc.) |
| Real-world examples | All 4 evidence exhibits are modeled on real phishing patterns: fake account-suspension, CEO/BEC wire fraud, prize-scam, **plus one legitimate control email** so learners practice telling good from bad, not just spotting "obviously fake" mail |
| Interactive quizzes | A **5-question scenario-based quiz** with instant feedback per answer, a progress bar, a final score + verdict ("Cleared for duty" / "Recommend retraining"), and a retake button |

---

## 🎨 Design concept

The module is framed as a **case file**, not a corporate slide deck — dark "investigation room" background, cream "evidence paper" email cards, and a highlighter-yellow marker used consistently to mark red flags, mirroring how a real investigator annotates evidence. This framing was a deliberate choice to make the content memorable instead of generic.

- **Color palette**: ink navy `#1B2330`, evidence paper `#F2EEE4`, highlighter `#F4D35E`, alert red `#C0445C`, investigator teal `#3E7C8A`
- **Typography**: Source Serif 4 (headlines — gives the "case file" gravity), Source Sans 3 (body copy), IBM Plex Mono (stamps/labels — evidence-tag feel)
- **Signature interaction**: click-to-reveal evidence annotations on each email exhibit, turning passive reading into active investigation

---

## ⚙️ Setup & Usage

No build step, no server, no dependencies.

```bash
git clone https://github.com/<your-username>/CodeAlpha_PhishingAwareness.git
cd CodeAlpha_PhishingAwareness
```

Then either:
- **Double-click `index.html`** to open it directly in your browser, or
- Enable **GitHub Pages** on the repo (Settings → Pages → deploy from `main` branch) to get a live shareable link for your LinkedIn post / submission.

---

## 🧩 Project Structure

```
CodeAlpha_PhishingAwareness/
├── index.html              # The entire training module (HTML + CSS + JS, single file)
├── README.md                 # This report
└── screenshots/
    ├── 01_hero.png
    ├── 02_spot_the_phish.png
    └── 03_field_test_quiz.png
```

---

## 🧠 Module Outline

1. **Briefing (Hero)** — frames why phishing matters: it's the entry point for most breaches, not a technical exploit.
2. **The Playbook** — the 4 social-engineering levers attackers combine: Urgency, Authority, Scarcity/Reward, Trust Transfer.
3. **The Evidence — Spot the Phish** — 4 inspectable email exhibits (3 phishing + 1 legitimate control sample) with click-to-reveal annotations.
4. **Field Manual** — 5 concrete, memorable habits that stop most phishing attempts.
5. **Field Test** — 5-question interactive quiz with live scoring and a final verdict.

---

## ⚖️ Ethical Note

All email examples are **fabricated for training purposes** — no real company, person, or domain is impersonated beyond well-known generic patterns (e.g., "PayPal-style" suspension emails) used purely for educational pattern recognition.

---

## 🙋 About This Submission

- **Internship**: Cyber Security, CodeAlpha
- **Task**: Task 2 — Phishing Awareness Training
- **Tech stack**: Plain HTML/CSS/JavaScript — no frameworks, no build tools, works offline

If you found this useful, feel free to ⭐ the repo!
