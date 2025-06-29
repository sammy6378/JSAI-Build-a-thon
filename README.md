
````markdown
# 🌿 Local Farming Advisor Chatbot

An AI-powered chat assistant designed to support small-scale farmers with personalized agricultural advice. Built with the [Azure OpenAI Chat Frontend Template](https://github.com/Azure-Samples/azure-openai-chat-frontend) and customized to serve the farming community in a simple, localized, and practical way.

---

## 🧩 Problem Statement

Small-scale farmers, especially in rural regions, often lack timely access to agricultural experts. This makes it difficult to get advice on:
- What crops to plant and when
- How to deal with pests or diseases
- Weather-aware decisions
- Soil preparation and fertilization techniques

Our solution aims to bridge this knowledge gap using AI.

---

## 🚀 Why This Template?

We chose the `azure-openai-chat-frontend` template because:
- It provides a ready-to-go chat interface
- It supports revisiting chat history and debugging
- It's lightweight and highly customizable
- It lets us plug in OpenAI models with minimal setup

This makes it perfect for transforming into a domain-specific farming advisor without starting from scratch.

---

## ✨ Customizations Made

| Feature                        | Customization Description                                                                 |
|-------------------------------|-------------------------------------------------------------------------------------------|
| 🔁 Chat Prompt                | Updated system prompt to simulate an agricultural expert                                 |
| 🌾 Domain Focus               | Tailored for local farming advice: maize, beans, pests, climate, soil health             |
| 🎨 UI Styling                 | Theming changed to green/brown tones representing nature/agriculture                     |
| 🌍 Region-Specific Hints      | Preloaded common questions like: “Best time to plant maize in Kenya?”                   |
| 📘 Branding                   | Added local branding title: “Local Farming Advisor”                                      |
| 📂 Structure                  | Cleaned up unused assets, added farming-related icons                                    |

---

## 🧠 Example Prompts You Can Try
- "What fertilizer should I use for maize in acidic soil?"
- "How do I deal with fall armyworm?"
- "What's the best planting time for beans in Kenya?"
- "How do I rotate crops for better soil?"

---

## 🛠️ Getting Started Locally

### Prerequisites
- [Node.js](https://nodejs.org/) installed
- [Azure Developer CLI (azd)](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/overview)
- Azure subscription
- OpenAI resource deployed in Azure (with API key)
- `git` installed

### Clone the Repo
```bash
azd init -t azure-openai-chat-frontend
````

### Run It

```bash
azd up
```

### Add Custom Config (optional)

You can modify the system prompt and region-specific advice in:

```js
/src/utils/systemPrompt.ts
```

---

## 📦 Folder Structure

```
/src
├── components      # UI components (chat box, messages, etc.)
├── styles          # Custom styles for farming UI
├── utils/systemPrompt.ts # Custom system prompt
├── App.tsx
```

---

## 🤝 Community Voting

If this project helps farmers or inspires you, upvote this issue in the AI + Cloud Build-a-thon community!

👉 [🔗 Project Submission Issue](#)

---

## 📸 Screenshots

> Add screenshots of the chat UI with a farming theme and sample responses from the bot.

---

## 📬 Future Improvements (Post-Submission)

* Integrate weather API for live forecasts
* Add local language support (e.g., Swahili)
* Save chat history to backend for follow-ups
* Enable voice input for accessibility

---

## 👨‍🌾 Built for Farmers, Powered by Azure + AI
