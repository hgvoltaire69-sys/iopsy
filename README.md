# OB Practice Exam (Lessons 3 to 5)

Static site, no build step. Files: `index.html`, `questions.js`, `README.md`.

## Push to GitHub
```
cd io-exam-site
git init && git add . && git commit -m "Practice exam site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/io-exam-site.git
git push -u origin main
```

## Deploy on Vercel
Import the GitHub repo at vercel.com/new. Framework preset: **Other**. Leave build command and output directory empty. Deploy.

## Antigravity
Open the folder (or clone the repo) in Antigravity. To preview locally, run `npx serve .` or `python3 -m http.server`.

## Add questions
Edit `questions.js`. Each line: `{l:lesson, q:"question", o:["A","B","C","D"], a:indexOfCorrect, e:"explanation"}`.
