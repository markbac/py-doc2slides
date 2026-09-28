# `py-doc2slides` — Markdown to PowerPoint (.pptx) Presentation Converter

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.9%2B-blue.svg)

A Python CLI and developer toolkit for converting Markdown technical documentation into styled **Microsoft PowerPoint (`.pptx`)** slide decks. Based on the `createdocs` tool set and `Convert_to_pptx.ps1` workflow.

---

## 🚀 Features

- **Automated Slide Splitting**: Splits Markdown documents into individual slides on `---` horizontal rules or H1/H2 `#` headers.
- **Title & Content Layouts**: Preserves Title slides, bullet point lists, and monospaced code blocks.
- **Reference Template Support**: Option to supply a custom PowerPoint template (`Template.pptx`).
- **Py-LogKit Integration**: Color-coded CLI logging.

---

## 🛠️ Installation

```bash
pip install -e .
```

---

## 💻 CLI Usage

```bash
# Convert single Markdown file to PowerPoint presentation
py-doc2slides Technical_Presentation.md -o Technical_Presentation.pptx

# Convert using custom reference template
py-doc2slides Presentation.md -r Template.pptx
```
