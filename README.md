# 🔍 CircleNSearch — macOS Screenshot Search Assistant

**CircleNSearch** is a lightweight macOS utility that allows you to draw a selection on the screen and instantly get results:

- 🔤 OCR (extract text with preserved line breaks)  
- 🌍 Translation into the selected language  
- 🖼️ Image analysis powered by GPT-4o Vision  
- 🗣️ Text-to-Speech output with voice, rate, and pitch controls  

---

## ✨ Features

- 📸 Quick screen selection with overlay window and hotkey  
- 🔤 OCR support for multiple languages  
- 🌍 Line-by-line translation (no merged paragraphs)  
- 🖼️ Image analysis (products, brands, tasks, etc.)  
- 🗣️ Text-to-Speech with customizable voices, speed, and pitch  
- 🎨 Flexible UI settings: font size, colors, opacity, window size  

---

## 🛠️ Tech Stack

- **Language**: Swift, SwiftUI, Combine  
- **Frameworks**: AppKit (overlay window), AVFoundation (TTS), URLSession  
- **3rd-party**: HotKey (SPM), OpenAI API (GPT-4o Vision + Translation)  

---

## 📸 Screenshots

<img width="299" height="231" alt="1" src="https://github.com/user-attachments/assets/a80f6993-d128-45f2-a099-0a55b8817511" />
<img width="559" height="639" alt="2" src="https://github.com/user-attachments/assets/ee7210a2-0029-4c1e-ae11-4a2ce3b02907" />
<img width="1290" height="715" alt="3" src="https://github.com/user-attachments/assets/2d5e88b2-3c65-4c56-902f-15454595523e" />

## DEMO Video
https://youtu.be/r7AvUjoKIs0

## 🚀 How It Works

1. User highlights an area of the screen.  
2. Captured image → OCR → structured text.  
3. Text translated line-by-line using JSON output to preserve format.  
4. Post-processing fixes spacing and punctuation.  
5. Result displayed in overlay window + optional voice output.  

---

## 🗺️ Roadmap

- [ ] Add history of results with export (PDF/Markdown)  
- [ ] User dictionary and inline corrections
      
---

## 🔒 About Code Access

This repository is a **showcase** with screenshots, demo GIFs, and project description.  
The full source code lives in a **private repository**.  

👉 If you are a recruiter or team lead and would like access to the code, please contact me directly and I’ll provide temporary read-only access.

---

## 👨‍💻 Author

Edward Gasparian — iOS/macOS Developer  
- GitHub: [totSamyGaspar](https://github.com/totSamyGaspar)  
- Email / Telegram: *available on request*  
