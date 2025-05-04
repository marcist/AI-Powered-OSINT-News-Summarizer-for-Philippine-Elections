# 🇵🇭 AI-Powered OSINT News Summarizer for Philippine Elections

A Google Colab-based tool that automatically searches, extracts, and summarizes Philippine news articles about election candidates using natural language processing (NLP). Built for **open-source intelligence (OSINT)** and civic research.

![Demo](https://user-images.githubusercontent.com/your-demo.gif) <!-- Replace with actual demo/screenshot if available -->

---

## 🧠 What It Does

- ✅ Lets you **select a candidate** from an official list
- 🔍 Searches trusted Philippine news sources via Google
- 📄 Scrapes article content
- ✨ Uses **BART (facebook/bart-large-cnn)** to generate a concise summary
- ⚠️ Includes a disclaimer on content use

---

## 📰 News Sources Covered

- [ABS-CBN](https://news.abs-cbn.com)
- [PhilStar](https://philstar.com)
- [Rappler](https://rappler.com)
- [GMA News](https://gmanetwork.com)
- [Inquirer](https://inquirer.net)
- [The Manila Times](https://manilatimes.net)

---

## 🔧 How to Use (Google Colab)

> 💡 No installation needed if you use Google Colab!

1. 📂 Open the Colab notebook here: [🔗 View in Colab](https://colab.research.google.com/drive/1H00zrFzopSw8_D35yJ2LDdjf2WZpcAkQ?usp=sharing)
2. 🔘 Select a candidate from the dropdown
3. 🖱 Click `Search News`
4. 📊 Wait as it searches and summarizes top 5 relevant news articles

---

## 📦 Dependencies

Automatically handled in Colab, but for local use:
```bash
pip install requests beautifulsoup4 googlesearch-python newspaper3k transformers ipywidgets tqdm
