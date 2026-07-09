# English Verbs Drill — CEFR A2 → C1

Interactive verb conjugation exercise with gamification, sentence practice, and IELTS/TOEFL vocabulary.

## Features
- **Bilingual interface** — toggle between English (default) and Portuguese with the EN/PT switch in the header; the translation column always targets Portuguese regardless of the interface language
- **114 verbs** organized by CEFR level (A2 · B1 · B2 · C1)
- **12 tenses** including all Perfect Continuous forms
- **Sentence practice** — mini exercises with contextual fill-in-the-blank
- **Stative verb warnings** on Continuous tenses
- **12 academic verbs** for IELTS/TOEFL (indicate, demonstrate, fluctuate, analyze...)
- Affirmative / Negative / Interrogative examples for every tense
- Feedback with rules, not answers

---

## 🚀 Deploy to Surge.sh (1 minute)

```bash
# 1. Install surge if you don't have it
npm install -g surge

# 2. Deploy (choose your domain)
surge . language-verbs.surge.sh

# Or use the npm script (edit domain in package.json first)
npm run deploy
```

Your site will be live at: `https://language-verbs.surge.sh`

---

## 📦 Push to GitHub

```bash
# 1. Initialize repo
git init
git add .
git commit -m "feat: English verb drill — CEFR A2 to C1 with sentence practice"

# 2. Create repo on GitHub, then:
git remote add origin https://github.com/YOUR_USERNAME/english-verbs-drill.git
git branch -M main
git push -u origin main
```

---

## 💻 Open with Claude Code

```bash
# Clone your repo
git clone https://github.com/YOUR_USERNAME/english-verbs-drill.git
cd english-verbs-drill

# Open with Claude Code (desktop app)
claude .
```

Or inside Claude Code terminal:
```bash
# Preview locally
npm install
npm start
# → opens at http://localhost:3000
```

---

## 📁 Project Structure

```
english-verbs-drill/
├── index.html      ← The complete exercise (single file)
├── package.json    ← Deploy scripts
├── CNAME           ← Surge domain config
├── .gitignore
└── README.md
```

---

## 🗺️ Roadmap
- [ ] Gamification: XP, streaks, levels
- [ ] Spaced repetition system
- [ ] Context-based exercises (IELTS writing samples)
- [ ] Score persistence (localStorage or backend)
- [ ] Mobile responsive improvements

---

*Built for LogoAliii (@logoaliii) — English learning content for Brazilian Portuguese speakers.*
