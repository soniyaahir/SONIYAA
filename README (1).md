# 🧠 NoteMap AI — Handwritten Notes → Smart Mind Map Generator

## Overview
An AI-powered Streamlit app that converts handwritten notes (image or text) into structured visual mind maps using Claude Vision + NLP.

---

## ⚡ Quick Setup

### 1. Install dependencies
```bash
pip install -r requirements.txt
```

### 2. Get your Anthropic API key
Sign up at https://console.anthropic.com and copy your API key.

### 3. Run the app
```bash
streamlit run app.py
```

The app opens at **http://localhost:8501** in your browser.

---

## 🎯 How to Use

1. **Enter your API key** in the left sidebar
2. **Upload an image** of handwritten notes (JPG, PNG, WEBP) — OR — **paste typed text** in the text box
3. Click **"⚡ Generate Mind Map"**
4. Get your:
   - 🌳 **Visual mind map** (downloadable PNG)
   - 📑 **AI summary** of the notes
   - 🏷️ **Key concepts / keywords**
   - 📄 **Structured JSON** of the full hierarchy

---

## 📁 Project Structure

```
mindmap_generator/
├── app.py              ← Main Streamlit app
├── requirements.txt    ← Python dependencies
└── README.md           ← This file
```

---

## 🔧 Features

| Feature | Status |
|---|---|
| Handwritten image OCR (via Claude Vision) | ✅ |
| Text input mode | ✅ |
| Auto image preprocessing (contrast, sharpening, denoise) | ✅ |
| AI keyword extraction | ✅ |
| Hierarchical mind map generation | ✅ |
| Color-coded branches | ✅ |
| AI summary generation | ✅ |
| PNG download of mind map | ✅ |
| JSON export of structured data | ✅ |
| Dark mode professional UI | ✅ |

---

## 💡 Tips for Best Results

- Use **good lighting** when photographing notes
- Works best with **clear, dark ink** on white/light paper
- If OCR struggles, use the **text paste** option instead
- For complex notes, break them into **sections** per upload

---

## 🛠️ Tech Stack

- **Claude Sonnet** (Anthropic) — Vision OCR + NLP structuring
- **Streamlit** — Web UI
- **Matplotlib** — Mind map rendering
- **Pillow** — Image preprocessing

---

*Built for academic and professional productivity. Powered by Claude AI.*
