# test-n8n

# 🤖 AI Pull Request Reviewer with n8n + GitHub

Automatically reviews Pull Requests using AI and posts feedback directly on GitHub.

---

## 🚀 Features

- Trigger on GitHub Pull Request events
- Fetch PR code changes automatically
- AI-powered code review (bugs, security, performance, quality)
- Posts review comments back to PR
- Fully self-hostable or n8n cloud

---

## 🧠 Architecture Flow

GitHub Webhook  
→ n8n Webhook Trigger  
→ Fetch PR Diff  
→ AI Agent Review  
→ Comment on Pull Request  

---

## 🔧 Requirements

- GitHub Personal Access Token (PAT)
- n8n (Cloud or Self-host)
- AI Provider (OpenAI, Anthropic, etc.)

---

## 🔐 GitHub Token Permissions

Create a token with:

