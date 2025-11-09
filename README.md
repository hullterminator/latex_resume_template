# 📄 Anonymized LaTeX Résumé Template  

[![LaTeX](https://img.shields.io/badge/LaTeX-Template-blue?logo=latex&logoColor=white)](https://www.latex-project.org/)
[![PDF](https://img.shields.io/badge/Preview-PDF-success?logo=adobeacrobatreader&logoColor=white)](./resume_Template.pdf)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A **completely anonymized and modular LaTeX résumé** built with `tcolorbox`, `tabularx`, and minimalist design principles — perfect for professionals who want a clean résumé layout without revealing personal data.

---

## 🧩 Overview

This repository contains a **professionally structured résumé template** derived from a detailed engineering résumé and converted into a **fully anonymized, placeholder-only version** for public sharing or reuse.

Every identifiable element — names, companies, tools, projects, certifications, and technologies — has been replaced with consistent, neutral placeholders such as `Organization A`, `Project B`, `Tool C`, and `Protocol A`.

You can safely use this as a **base template** to:
- Build your own LaTeX résumé
- Maintain consistent formatting across versions
- Demonstrate layout skills without sharing personal information  

---

## 🎨 Features

✅ Clean, modern typographic layout using `extarticle`  
✅ Fully structured with `tcolorbox` section containers  
✅ Compact bullet style for professional readability  
✅ Adaptive tables for education and experience  
✅ Consistent placeholder scheme across the document  
✅ Pre-configured for A4 output with fine-tuned margins  
✅ 100% compilable with **pdfLaTeX**

---

## 🧱 Section Layout

Includes the following sections:

- **Professional Summary**
- **Education**
- **Technical Skills**
- **Experience**
- **Projects**
- **Competitions & Challenges**
- **Certifications**
- **Interests**

Each section is enclosed in a `tcolorbox` for clear separation and readability.

---

## 🔐 Anonymization Rules

| Category | Replacement Pattern |
|-----------|--------------------|
| Dates | `01 Jan 2021` / `Jan 2021` |
| Names & Roles | `Candidate A`, `Role A`, `Role B` |
| Organizations | `Organization A`, `Organization B` |
| Projects | `Project A` … `Project N` |
| Tools / Platforms | `Tool A`, `Tool B`, `Platform A` |
| Protocols / Interfaces | `Interface A`, `Protocol A` |
| Cities / Countries | `Your City`, `Your Country` |
| Contact Info | `your.email@example.com`, `+91-0000000000` |
| Links | `linkedin.com/in/yourusername`, `github.com/yourusername` |

---

## 🧰 Requirements

You’ll need LaTeX installed.  
To compile locally, run:

```bash
pdflatex resume_placeholders_final.tex
```

Or open directly on **Overleaf**, **TeXstudio**, or **VS Code (LaTeX Workshop)**.

---

## 🚀 Usage

1. **Clone or download** this repository.  
2. Open `resume_placeholders_final.tex`.  
3. Replace placeholders (`Project A`, `Organization A`, etc.) with your own data.  
4. Recompile to generate your résumé PDF.  

Example:

```tex
\item \textbf{Hardware Design Engineer} 
\hfill \textit{\textbf{Techlanz Pvt. Ltd., Bangalore}} 
\hfill \textit{Jul 2024 -- Present}
```
➡ Replace with your details.

---

## 🧩 Folder Structure

```
.
├── resume_placeholders_final.tex   # The LaTeX source
├── README.md                       # This file
└── resume_placeholders_final.pdf   # (Optional) compiled preview
```

---

## 💡 Tips

- Use this as a **base layout** for any technical résumé (engineering, IoT, research, etc.).  
- Adjust margins or fonts in `geometry` if printing.  
- Keep bullet points concise — one line per point looks best.  
- Add new `tcolorbox` sections as needed.

---

## 📘 License

This project is released under the **MIT License** — free for use, modification, and redistribution with attribution.

---

## 💬 Author


Maintained & published by: *hullterminator*  
 

---

> “Design your résumé like your circuit — structured, minimal, and failure-proof.” ⚙️

---
