# Smart Reply Backend (Spring Boot) 💬🧠

This is the backend for the **Smart Reply AI** application. It provides RESTful endpoints to process email inputs and generate AI-powered replies using the Gemini API.

---

## 🔗 Live API Endpoint

> Replace with your deployed URL:

**Base URL:** `https://your-render-backend.onrender.com/api`
---

## ⚙️ Technologies Used

- Java 17
- Spring Boot
- Maven
- Google Gemini Pro API
- Deployed on Render
- DockerFile

---
## 📦 Project Structure
<img width="403" height="696" alt="image" src="https://github.com/user-attachments/assets/7a77fc36-2b8b-4fff-8ea0-046d45aa9c5e" />

## 🧪 API Usage

### POST `/api/email/generate`

**Request Body:**
```json
{
  "emailContent": "I'd like to reschedule our meeting...",
  "tone": "formal"
}
```

## Environment Variable
GEMINI_API_URL=https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-pro:generateContent
GEMINI_API_KEY=your_gemini_api_key

# Clone the repo
git clone https://github.com/your-username/smart-reply-sb.git

cd smart-reply-sb

# Build the project
./mvnw clean package -DskipTests

# Run the project
./mvnw spring-boot:run
