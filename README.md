from flask import Flask, render_template

app = Flask(__name__)

@app.route("/")
def home():
    return render_template("index.html")

if __name__ == "__main__":
    app.run(host="0.0.0.0", port=5000, debug=True)# Universal MP4 Player

AI MP4 Player with FFmpeg, Whisper, Translator and TTS.

Status: Under Development
