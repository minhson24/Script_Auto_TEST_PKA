# Quiz Auto (Gemini) — Tampermonkey Script

A Tampermonkey userscript that **auto-answers multiple-choice quizzes** using Google Gemini API.  
It extracts the question & options from the page, asks Gemini once per question, selects the answer, and clicks **Next**.  

<p align="center">
  <img src="https://github.com/user-attachments/assets/3e4b201d-0260-4cc2-97ce-c9905bd33897" alt="Quiz Auto Gemini Screenshot" width="470"/>
</p>

---

## ✨ Features
- 🚀 **One API call per question** → cost efficient.  
- 🔒 **Strict mode** → no random guessing, stops if uncertain.  
- 🔄 **Multi-key rotation** → switch API keys when quota/limit reached.  
- ⏱️ **Customizable** → set number of questions & delay per question.  
- 🖥️ **Floating control panel** → start/stop, key manager, auto-rotate toggle.  
- 🔁 **Persistent state** → continues across page reloads.  

---

## ⚙️ Setup
1. Install [Tampermonkey](https://www.tampermonkey.net/).  
2. Add the script (`quiz-auto-gemini.user.js`).  
3. Open your quiz site → the control panel appears at bottom-right.  

---

## ▶️ Usage
- **⚙️ Keys** → paste your Gemini API keys (one per line).  
- **#Q** → number of questions to auto-answer.  
- **Delay(s)** → wait time before moving to next question.  
- **Auto-rotate keys** → toggle automatic key switching on quota errors.  
- **🤖 Start** → begin automation.  
- **⏹ Stop** → stop automation immediately.  

---

## 📝 Notes
- Works on standard quiz pages with visible question + multiple-choice answers.  
- Accuracy depends on Gemini’s domain knowledge.  
- Recommended: keep multiple valid API keys to avoid interruptions.  
- Intended for **personal/educational use only**.  
