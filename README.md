# 📝 Smart Scribe – AI-Powered Email Reply Assistant

> ✨ *Think Less. Write Smart.*  
> **Smart Scribe** is your personal AI writing assistant built with 💛 for emails. It crafts context-aware replies in seconds — professional, casual, or just a little witty — powered by the Gemini API and Spring Boot.

---

## 🚀 Why Smart Scribe?

Imagine staring at your inbox, dreading the mountain of email replies waiting.  
Now imagine clicking one button and letting AI do it for you.  
That's **Smart Scribe**.

Built using:
- 🔧 **Spring Boot** for a rock-solid backend  
- 🧠 **Google Gemini API** for intelligent reply generation  
- 🎨 **React & Material UI** for a slick, responsive UI  

---

## 🎯 Features

✅ Generate context-based email replies  
✅ Choose your preferred tone: *Professional*, *Casual*, or *Sarcastic*  
✅ Clean React interface with real-time response display  
✅ Copy-to-clipboard feature for easy reply pasting  
✅ API tested with Postman and integrated with WebClient  
🚫 *No Chrome extension yet — stay tuned for the next version!*

---

## 📸 Demo

> Here’s a sneak peek of the UI and tone toggle feature!

![WhatsApp Image 2025-06-19 at 12 47 02_2d40d5db](https://github.com/user-attachments/assets/c48520cc-9127-4e0f-b658-ee53415a670d)
![WhatsApp Image 2025-06-19 at 12 47 22_b73802ac](https://github.com/user-attachments/assets/60b28ff2-62da-4702-a241-f4d49686c645)
![WhatsApp Image 2025-06-19 at 12 48 06_08c94fd3](https://github.com/user-attachments/assets/03acac87-3c9b-45b1-9db5-dcb5ca713a83)




---

## 🛠️ Tech Stack

| Layer        | Tech Used                            |
|--------------|--------------------------------------|
| Backend      | Spring Boot, Java, Maven, WebClient  |
| AI Model     | Google Gemini API                    |
| Frontend     | React.js, Material UI                |
| Dev Tools    | Postman, VS Code                     |

---

## 📦 How to Run Locally

### 🧠 Backend (Spring Boot)

1. Clone the repo:

   ```bash
   git clone https://github.com/YourUsername/smart-scribe.git
   cd smart-scribe/backend
   ```

2. Add your Gemini API key to `application.properties`:

   ```properties
   gemini.api.key=YOUR_API_KEY_HERE
   ```

3. Run the project:

   ```bash
   ./mvnw spring-boot:run
   ```

### 🎨 Frontend (React)

1. Navigate to the frontend:

   ```bash
   cd ../frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the app:

   ```bash
   npm start
   ```

---

## 🔐 API Testing with Postman

Example cURL:

```bash
curl -X POST http://localhost:8080/api/generate-email \
-H "Content-Type: application/json" \
-d '{"emailContent":"Thank you for the follow-up","tone":"professional"}'
```

Or import the cURL into Postman to test with your custom body.

---

## 🧠 Behind the Scenes

- **Prompt Engineering**: Dynamic prompts are crafted using user email and tone.  
- **WebClient**: Used for async Gemini API calls.  
- **ObjectMapper**: Handles JSON response parsing.  
- **CORS Enabled**: Smooth integration between backend & frontend.  

---

## 🔮 What’s Next?

- 🔧 Chrome Extension for Gmail integration  
- 🌐 Multi-language tone support  
- 📚 AI memory for contextual thread replies  
- 🖼️ Dark mode (because aesthetics matter)

---

## ✍️ Author

Made with 💡 by **Juhi Agarwal**  
📫 [juhiagarwal2003@gmail.com](mailto:juhiagarwal2003@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/juhi-agarwal-005b2625a/) | 🖥️ [GitHub](https://github.com/JuhiAgarwal03)

---

## 🧑‍💻 Want to Contribute?

Feel free to fork the repo, open an issue, or raise a PR.  
Let’s make inboxes smarter, together. 🤖

---

## 📄 License

MIT License. You’re free to remix, share, and improve – just give credit!

---
