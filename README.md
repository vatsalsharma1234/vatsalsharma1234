<h1 align="center">Hi, I'm Vatsal Sharma 👋</h1>
<h3 align="center">Data Scientist · Machine Learning Engineer · Competitive Programmer</h3>

<p align="center">
  <a href="mailto:vatsalkps12345@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://tinyurl.com/VatsaLSharma"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/vatsalsharma1234"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://leetcode.com/u/minndflayer/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white" alt="LeetCode"/></a>
</p>

---

### 👋 About Me

I build systems that turn messy, real-world data into decisions people can actually act on — and I solve problems fast, having worked through 650+ competitive programming challenges to sharpen the algorithmic thinking that underpins good data science.

Some of what that's looked like in practice:

- Built a tool that gives people faster insight into skin conditions by combining a photo of the affected area with their own description of symptoms — the kind of system that could widen access to early screening where a dermatologist isn't around the corner.
- Built a tool that shows job seekers exactly why an automated hiring system might be rejecting their resume, and precisely what to fix — turning a black-box process into something actionable.
- Built an investment simulator that replaces gut-feeling assumptions about "average returns" with a real, year-by-year ledger based on actual historical market data.
- Built a face-recognition attendance system that removes both the friction of manual roll-call and the fact that nobody usually reviews the resulting data.
- Solved 650+ problems across competitive programming, reaching a peak rating of 1844 — top 6% globally.

---

### 🧰 Tech Stack

**Data Science & Machine Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white)

**Competitive Programming & Core CS**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![STL](https://img.shields.io/badge/C++_STL-00599C?style=flat-square)
![DSA](https://img.shields.io/badge/Data_Structures_%26_Algorithms-3776AB?style=flat-square)

**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

### 🚀 Projects

#### 🩺 Skin Disease Risk Classifier
[`disease-classifier`](https://github.com/vatsalsharma1234/disease-classifier)

Skin conditions are one of the most commonly delayed diagnoses — either because a dermatologist isn't easily reachable, or because a condition looks minor enough to be ignored until it isn't. This project set out to close some of that gap.

The system takes two inputs at once — a photo of the affected area, and a plain-language description of the symptoms a person is experiencing — and combines both to identify the most likely condition out of 21 categories. Rather than leaning on a single signal, it works the way a real diagnosis would: what something looks like, plus what the patient says about it. The two predictions are merged with adjustable weighting, so the system can be tuned toward trusting the image or the description more, depending on the situation.

Because a wrong call in a health context carries real consequences, the model wasn't just checked for overall accuracy — it was stress-tested across multiple evaluation angles to make sure it wasn't quietly failing on harder or less common categories, the kind of blind spot that matters most when the output could actually influence someone's next step.

#### 📄 Resume–Job Match & ATS Transparency Tool
[`resume-analysis`](https://github.com/vatsalsharma1234/resume-analysis) · built during a volunteer engagement with **Obcidian Group**

Most resumes today are filtered by automated hiring software before a human ever sees them — and most candidates have no idea why they were rejected. This project builds the candidate's side of that same lens.

It reads a resume directly out of its PDF or DOCX file, compares it against a specific job description the same way an ATS would, and — unlike the actual ATS — shows the candidate exactly what happened: a similarity score, which skills matched, and which ones are missing. Instead of guessing why an application went nowhere, someone gets a concrete, fixable answer.

#### 📈 Compound Ledger — Historical Investment Backtester
[`compound-ledger-backtester`](https://github.com/vatsalsharma1234/compound-ledger-backtester)

Most people planning to invest long-term rely on rough, oversimplified assumptions about "average annual return" rather than seeing what actually happened, year by year, in the real market. This tool replaces the assumption with the data.

Someone can plug in a starting amount and a yearly contribution, choose from real historical returns across stocks, indices, crypto, and gold, and watch it compound out into an actual year-by-year ledger — complete with CAGR, gain/loss, and a benchmark comparison. It turns "compounding is powerful" from a slogan into something a person can actually see happen with numbers they chose themselves.

#### 🎥 Real-Time Face Recognition Attendance System
[`face-attendance-system`](https://github.com/vatsalsharma1234/face-attendance-system) · built during an internship at **Vault of Code**

Manual attendance has two quiet failure modes: it's easy to fake (proxy attendance for someone who isn't there), and once it's recorded, almost nobody goes back and actually reviews it.

This project addresses both. People register by having their face sampled through a webcam; a local recognition model is trained on that data; and from then on, attendance is captured automatically and in real time, with duplicate-proof, timestamped logging so the same person can't be marked twice in a day. On top of that, a dashboard was built specifically so the resulting records don't just sit in a file somewhere — attendance can be filtered by date or name and visualized, so the data actually gets used instead of ignored.

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=vatsalsharma1234&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vatsalsharma1234&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" height="165"/>
</p>

---

### 🏆 Achievements

- 🥇 **Competitive Programmer** — 650+ problems solved, peak rating **1844** (top 6% globally) · [LeetCode profile](https://leetcode.com/u/minndflayer/)
- 🎖️ **Head Boy, Class 12** — elected to lead the senior student body; served as the primary point of coordination between students and school administration
- 📜 **Microsoft Certified: Generative AI** · [View certificate](https://drive.google.com/file/d/1lt3E0nKwwwizmIWcY2-YDDapd2pTvvla/view)

---

<p align="center"><i>Open to Data Science and Machine Learning opportunities — let's connect.</i></p>
