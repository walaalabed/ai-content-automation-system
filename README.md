# AI Content Automation System

An AI-powered content automation workflow built with **n8n**, **OpenAI**, **Tavily Search API**, and **Google Sheets**.

The workflow automatically researches a topic, generates AI-powered content for multiple platforms, and stores the generated content in Google Sheets.

---

# Features

- Automated content generation
- AI-powered web research using Tavily Search API
- LinkedIn post generation
- X (Twitter) post generation
- SEO blog article generation
- Google Sheets integration
- End-to-end automated workflow

---

# Technologies Used

- n8n
- OpenAI GPT-4.1 Mini
- Tavily Search API
- Google Sheets API
- REST API

---

# Workflow

1. Google Sheets detects a new content request.
2. The workflow extracts the content topic and target audience.
3. Tavily Search API researches the latest information related to the topic.
4. Research results are processed and aggregated.
5. OpenAI generates:
   - A professional LinkedIn post
   - An engaging X (Twitter) post
   - An SEO-optimized blog article
6. The generated content is automatically saved back into Google Sheets.

---

# Files

- ai-content-automation-system.json
- workflow.jpg

---

# Workflow

![workflow](workflow.jpg)

---

# Example Use Cases

- Marketing campaign content creation
- Social media automation
- AI-powered content marketing
- Blog writing automation
- Multi-platform content generation

---

# Future Improvements

- Add support for Facebook and Instagram content generation
- Publish content automatically to social media platforms
- Generate AI-powered images for posts
- Add content approval workflow before publishing
- Support multiple content tones and writing styles
- Generate content in multiple languages
