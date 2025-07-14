# 🎵 Expremusic – Emotion-Based Spotify Playlist Recommender

**Expremusic** is an intelligent facial emotion recognition app that analyzes your current expression and **automatically plays a Spotify playlist** that matches your mood.

Smile? Chill beats.  
Frown? Lo-fi or deep cuts.  
No emotion? Let the AI decide what you need most.

---

## 🧠 What It Does

Using a trained deep learning model (`emotion_model.keras`), the app reads your facial expression from a webcam feed or image input and matches it to a mood category. Based on the result, it triggers a curated **Spotify playlist** through the `emotion_spotify_player` module.

---

## 💡 Use Cases

- 🔄 Auto-tune your music to your mood without lifting a finger
- 💻 Great for productivity, stress relief, or just vibing out
- 🎧 Mood-based ambient playlists for focus, workouts, or sleep

---

## 🚀 How It Works

1. Capture a facial image (via webcam or input image)
2. Use CNN-based model to predict the emotion
3. Map predicted emotion → specific Spotify playlist
4. Redirect user to corresponding Spotify link

---

## 🛠 Tech Stack

- **Language:** Python  
- **Model:** Keras (CNN for facial emotion recognition)  
- **Interface:** Jupyter Notebook (prototype stage)  
- **Music Integration:** Spotify Web API  
- **Files:**
  - `emotion_model.keras`: Trained emotion detection model
  - `emotion_spotify_player`: Maps emotions → Spotify playlists
  - `Untitled1.ipynb`: Main driver notebook
  - `requirements.txt`: Dependencies list

---

## 📦 Installation

1. Clone the repo:

```bash
git clone https://github.com/theadhithyankr/expremusic.git
cd expremusic
pip install -r requirements.txt
jupyter notebook
