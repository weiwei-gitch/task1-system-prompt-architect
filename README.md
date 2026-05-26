# Task 1 — The System Prompt Architect

## 🎯 Overview
This project is part of a prompt engineering challenge. The goal was to design a **complex system prompt** that transforms a generic AI into a professional **Luxury Travel Consultant** with a strict persona, knowledge boundaries, and consistent behavior under pressure.

---

## 🧠 What I Built
A fully engineered system prompt for **Vivienne Beaumont**, Senior Luxury Travel Consultant at *Élite Voyages* — a high-end travel agency AI assistant.

The system prompt includes:
- ✅ **Strict Persona** — name, tone, personality, and communication style
- ✅ **Knowledge Boundaries** — what she knows and what she refuses to discuss
- ✅ **Conditional Discount Logic** — rules for when and how to offer deals
- ✅ **Competitor Handling** — graceful deflection without naming rivals
- ✅ **5 Few-Shot Examples** — demonstrations of perfect responses
- ✅ **Hard Constraints** — forbidden words, banned behaviors, tone rules

---

## 🛠️ Tools Used
- Claude (Anthropic)
- ChatGPT (GPT-4)
- HTML / CSS / JavaScript (for the interactive showcase page)

---

## 📁 Files in This Repo

| File | Description |
|------|-------------|
| `index.html` | Interactive showcase of the full system prompt |
| `README.md` | Project overview and documentation |
| `test-questions.md` | Test questions used to verify the prompt works |
| `screenshots/` | Screenshots of the AI responding in character |

---

## 🚀 How to Use the System Prompt

1. Open `index.html` and click **"Copy Full System Prompt"**
2. Go to [claude.ai](https://claude.ai), [chat.openai.com](https://chat.openai.com), or [gemini.google.com](https://gemini.google.com)
3. Paste the system prompt at the start of a new conversation
4. Start chatting — the AI will respond as Vivienne Beaumont

---

## 🧪 Testing

The prompt was tested against difficult scenarios including:
- Identity challenges ("Are you a bot?")
- Competitor price comparisons ("Booking.com has it cheaper")
- Out-of-scope requests ("Book me a budget economy flight")
- Budget pushback (activates discount logic)
- Rude or skeptical customers

In all cases, the AI maintained character without breaking persona.

---

## 📌 Key Prompt Engineering Techniques Used

- **Persona Engineering** — giving the AI a name, role, and employer
- **Few-Shot Prompting** — 5 example conversations showing ideal behavior
- **Negative Constraints** — explicit list of forbidden words and behaviors
- **Conditional Logic** — if/then rules for discount triggers
- **Knowledge Scoping** — defining exact domain boundaries
- **Tone Anchoring** — sensory language instructions and style rules
