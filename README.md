🚀 SubShift — Subtitle Translator

SubShift is a modern, browser-based subtitle translator that allows you to upload .srt or .vtt files, automatically detect the language, translate subtitles, edit them in real-time, and export the final result — all without installing anything.

⚡ Works entirely in your browser
🎬 Designed for creators, editors, and learners
🌐 Powered by free translation API

✨ Features
📁 File Upload
Drag & drop or click to upload subtitle files
Supports:
.srt
.vtt
🌍 Automatic Language Detection
Detects source language using API
Uses first few subtitle lines for accuracy
Option to manually override detected language
🔤 Multi-Language Support
Translate between major languages:
English
Chinese
Spanish
Hindi
Arabic
French
Russian
Portuguese
German
Japanese
⚡ Fast Translation
Translates subtitles line-by-line
Shows live progress bar
Handles API limits with smart delays
Fallback: keeps original text if translation fails
✏️ Built-in Subtitle Editor
View original + translated text side-by-side
Edit translations directly
Reset individual lines or all edits
Clean and responsive UI
📥 Export Options
Download translated subtitles as:
.srt
.vtt

File naming format:

filename_source-target.srt
🖥️ Demo Workflow
Upload subtitle file
Auto-detect language
Select target language
Translate subtitles
Edit if needed
Download final file
🧠 How It Works
1. Parsing
Reads subtitle structure from .srt / .vtt
Extracts:
Index
Timestamp
Text lines
2. Language Detection

Uses:

MyMemory Translation API (autodetect)
3. Translation
Sends requests per subtitle line
Combines multi-line subtitles intelligently
Splits translated text back into lines
4. Editing System
Stores:
Original translation
User-edited version
Allows reset anytime
5. Export
Rebuilds subtitle file format
Preserves timing and structure
🛠️ Tech Stack
HTML5
CSS3 (Modern UI with variables)
Vanilla JavaScript (No frameworks)
MyMemory Translation API
📂 Project Structure
SubShift/
│
├── index.html        # Main application (UI + logic)
├── favicon.png       # App icon
└── README.md         # Project documentation
🚀 Getting Started
1. Clone or Download
git clone https://github.com/your-username/subshift.git
2. Open in Browser

Just open:

index.html

No server required ✅

🌐 Hosting

You can host this project for free using:

GitHub Pages
Netlify
Vercel
GitHub Pages Steps:
Upload repo
Rename main file to index.html (already done ✅)
Enable Pages in repo settings
⚠️ Limitations
Depends on MyMemory API limits
Slower for large subtitle files
Internet connection required
Translation quality depends on API
💡 Pro Tip

You can increase free API usage by adding your email:

?de=youremail@gmail.com
🔒 Privacy
Files are processed locally in your browser
Only text is sent to translation API
No file uploads to servers
🎯 Use Cases
🎬 Movie subtitle translation
📺 YouTube subtitle editing
🌍 Language learning
🧑‍💻 Content localization
📸 UI Highlights
Dark modern theme 🌙
Smooth animations
Step-by-step workflow
Responsive layout
🧩 Future Improvements
🔥 Batch translation optimization
🌐 More language support
💾 Save projects locally
🤖 AI-powered translation (OpenAI / DeepL)
📱 Mobile optimization
👨‍💻 Author

Gavindu Kavishka

⭐ Support

If you like this project:

⭐ Star the repo
🍴 Fork it
🛠️ Improve it
📜 License

This project is free to use for personal and educational purposes.
