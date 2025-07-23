      
# 🗣️ Echo – Real-Time Voice AI Assistant

Echo is a sarcastic, classy voice assistant built with [LiveKit Agents](https://docs.livekit.io/agents/) and Google's real-time voice model. It responds in one-liners, fetches live weather data, searches the web, and interacts with you — just like a personal butler with an attitude.

Demo on my LinkedIn Account [Demo Here](https://www.linkedin.com/posts/muhammad-haroon-a097a9342_justbuiltthis-voiceai-aiprojects-activity-7353857414342877185-ibDm/) 

---

## 💡 Features

- 🎙️ Real-time voice interaction using Google Realtime Voice API
- 🧠 Custom personality (sarcastic + classy butler)
- 🌐 Web search powered by DuckDuckGo
- ☁️ Live weather reports using `wttr.in`
- 🖥️ Terminal version ready — frontend version can access camera
- 🆓 100% free and open-source

---

## 🚀 How It Works

Echo uses:

- `LiveKit Agents` for voice interaction
- `LangChain Tools` for web search
- `Google Voice Model (Aoede)` for natural responses
- Custom Python tools for weather and more

All responses follow a one-sentence butler-style format with sarcastic flair.

---

## 🛠️ Installation

1. **Clone the repo**

```bash
git clone https://github.com/mharoon1578/echo-voice-agent.git
cd echo-voice-agent
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Set up `.env` file**

Create a `.env` file in the root with the following:

```env
LIVEKIT_URL=your_livekit_url
LIVEKIT_API_KEY=your_livekit_api_key
LIVEKIT_API_SECRET=your_livekit_api_secret

GOOGLE_API_KEY=your_google_api_key

# Optional for email tool (currently disabled can be enable by uncommenting)
GMAIL_USER=your_email@gmail.com
GMAIL_APP_PASSWORD=your_app_password
```

4. **Run the assistant**

```bash
python agent.py
```

---

## 📦 Project Structure

```
├── agent.py             # Core agent logic and session start
├── prompt.py            # Agent personality and session instruction
├── tools.py             # Weather & web search tools
├── .env                 # Your API keys (not included in repo)
├── requirements.txt     # All dependencies
```

---

## 🤝 Contributing

Contributions, ideas, and forks are welcome!  
If you build a custom version of Echo, tag me — I'd love to see it.

---

## 🧠 Credits

- Built with [LiveKit Agents](https://livekit.io/)
- Voice by [Google Realtime Model](https://developers.generativeai.google)
- Web Search by [DuckDuckGo Search](https://duckduckgo.com/)
- Weather by [wttr.in](https://wttr.in)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🔗 Links

- 🔗 GitHub Repo: [github.com/yourusername/echo-voice-agent](https://github.com/mharoon1578/echo-voice-agent)
- 🎬 Demo Video: [Watch here](#)

---
