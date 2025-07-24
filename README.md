# 💼 Multi-Agent Sales Email Generator using OpenAI Agents SDK

This project uses the **OpenAI Agents SDK** to build a multi-agent, tool-using system that generates, formats, and sends sales emails

It generates sales emails with professional, witty, or concise tone, formats them in HTML, and sends them via SendGrid — all from a simple Gradio UI.

---

## 🧠 Key Features

- 🤖 **Multi-agent orchestration** (Sales Manager + Email Manager)
- 🧰 **Tool use and handoffs** between agents
- 🧾 **Structured output validation** with `pydantic`
- 🛡️ **Input and output guardrails** (profanity + tone matching)
- 📬 **Email delivery** via SendGrid
- 🧑‍💻 **Interactive Gradio UI**

---

## 🖼️ Gradio Interface Preview

![Gradio UI Screenshot](assets/screenshot.png)

---

## 🔧 Setup Instructions

1. **Clone this repo**  
   ```bash
   git clone https://github.com/your-username/openai-agentic-sales-email-app.git
   cd openai-agentic-sales-email-app
