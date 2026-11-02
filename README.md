NUSO AI - deploy on Vercel (free)
1. Put these on GitHub (new repo): index.html, and api/chat.js (folder "api").
2. vercel.com -> Add New -> Project -> import the repo -> Deploy.
3. Project Settings -> Environment Variables: add GEMINI_API_KEY = your key (from aistudio.google.com/apikey). Optional: GEMINI_MODEL (default gemini-2.5-flash).
4. Deployments -> Redeploy. Open your vercel.app link.
Never put the API key inside index.html.
