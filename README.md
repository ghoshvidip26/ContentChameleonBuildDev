# ContentChameleonBuildDev

**Upload a blog post → Get AI-generated Instagram captions, Twitter posts, and LinkedIn articles.**  
Powered by AI to help creators and marketers amplify their content across platforms effortlessly.

---

## 🚀 Features

- ✅ Upload a blog post (via file or raw text)
- 🤖 Automatically generate:
  - Short-form **Instagram captions**
  - Concise **Twitter/X posts**
  - Long-form **LinkedIn articles**
- 📄 Supports text and markdown blog content
- 🌐 API-based backend — ready for integration into any frontend or automation pipeline

---

## ⚙️ Built With

- **Buildship** (Serverless backend platform)
- **OpenAI/Gemini** (for content generation)

---

## 📦 API Endpoints

> Replace `<your-deployment-url>` with your actual Buildship URL.

### `POST /generate`

**Description:** Generate repurposed content from a blog post.

**Request Body:**

```json
{
  "title": "Your blog post title",
  "content": "Full text of the blog post"
}
