# 🧠 AI Journal API

This is the backend API for an AI-powered journal application that predicts the **mood** of user entries and provides **solutions or suggestions** based on emotional insights.

🔗 **Live Website:** [https://agriglance.ct.ws/](https://agriglance.ct.ws/)  
🌐 **Hosted On:** Render

---

## 📝 Features

- Accepts journal entries (text-based)
- Uses AI to analyze and predict emotional tone
- Provides feedback, advice, or insights based on mood
- RESTful API for frontend integration

---

## 🚀 API Endpoint

### `POST /api/journal`

Submit a journal entry to get mood analysis and AI-generated suggestions.

**Request Body:**
```json
{
  "title": "A Long Day",
  "content": "I felt overwhelmed today with all the work and barely got any time to rest."
}
