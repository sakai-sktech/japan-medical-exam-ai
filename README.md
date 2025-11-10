# 🧠 AI Responses to the Japanese National Medical Licensing Examination (JMLE)

This repository presents AI-generated responses to questions from the **Japanese National Medical Licensing Examination (JMLE)**, using multiple Large Language Models (LLMs) evaluated in parallel.

---

## 📄 Project Overview

- **Source**: Past JMLE questions (translated and formatted for AI input)
- **Models**: GPT-4, GPT-4o, Claude 3.5/3.7, Gemini 1.5, and other major LLMs
- **Method**: All models are queried simultaneously via [Tenbin AI](https://tenbin.ai), a platform that enables side-by-side evaluation
- **Question type**: Current focus is on **text-only questions** that do not require image interpretation
- **Output Format**: One Markdown file per question (e.g., `119-A11.md`)
- **SMAQ (custom ChatGPT-based assistant)**: Responses are provided separately in grouped batches (e.g., `119-A11-20_SMAQGPTs.md`)

---

## 🎯 Purpose

This project **does not aim to provide correct answers.**  
Instead, it offers:

- Insight into how LLMs **reason through clinical questions**
- A resource for medical learners and professionals to **compare, reflect, and verify**
- A platform to **stimulate critical thinking**, not passive memorization

> ✅ **Note**: At this stage, only **text-based questions** are included.  
> Image-based or visually dependent questions are excluded from initial publication.

---

## ⚠️ Disclaimer

> **This project is NOT intended for clinical decision-making.**

All content is for **educational, research, and reference purposes only**.  
The AI-generated responses may contain factual or medical inaccuracies.

Do **not use** this content for diagnosis, treatment, or any real-world clinical decision-making.

---

## 📎 Licensing

This repository is licensed under the [MIT License](./LICENSE).  
You are free to **use, adapt, distribute, or commercialize** the content with proper attribution.

---

## 📁 File Structure

- `119-A11.md` — One question and responses from multiple Tenbin-supported LLMs
- `119-A11-20_SMAQGPTs.md` — A batch of 10 questions answered using SMAQ (ChatGPT-based system)

Each LLM response includes:
- Final answer
- Explanation for the choice
- Reasoning against other options

---

## 🧾 Official Question Sources

The original questions used in this project are publicly released by Japan’s Ministry of Health, Labour and Welfare (MHLW):

- [119th National Medical Licensing Examination (2025, Reiwa 7)](https://www.mhlw.go.jp/seisakunitsuite/bunya/kenkou_iryou/iryou/topics/tp250428-01.html)
- [118th National Medical Licensing Examination (2024, Reiwa 6)](https://www.mhlw.go.jp/seisakunitsuite/bunya/kenkou_iryou/iryou/topics/tp240424-01.html)

Questions have been **reformatted and lightly adapted** for LLM input, but their original content remains under MHLW ownership.

---

## 📬 Contact

If you'd like to contribute, suggest improvements, or discuss AI in medical education, open a [GitHub Issue]([https://github.com/your-username/your-repo-name/issues](https://github.com/sakai-sktech/japan-medical-exam-ai/issues)) or contact the project owner.

---

## 🌐 Keywords

`AI in Medicine` · `JMLE` · `LLM Clinical Reasoning` · `Tenbin AI` · `Prompt Evaluation` · `Medical NLP` · `SMAQ`
