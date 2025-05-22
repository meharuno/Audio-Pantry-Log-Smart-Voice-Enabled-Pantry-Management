# 🔊 Audio-Pantry-Log-Smart-Voice-Enabled-Pantry-Management
Audio Pantry Log is an intuitive voice-powered app designed to help households effortlessly manage their pantry inventory.By simply recording short voice notes about what’s available at home, users can maintain an up-to-date inventory, track quantities and expiration dates, and generate smart shopping lists to avoid overstocking and reduce food waste.

Leveraging cutting-edge speech-to-text technology alongside Perplexity Sonar’s powerful natural language understanding, this app transforms casual voice inputs into actionable insights for smarter grocery management. 

## 🧠 Features
- Voice Recording Input: Quickly add pantry items by speaking naturally (e.g., “We have 2 liters of milk and 5 eggs.”)

- Automatic Transcription & Parsing: Converts speech to text and extracts items, quantities, and expiration info using Perplexity Sonar.

- Inventory Management: Keeps track of current pantry stock with quantities and expiry dates.

- Smart Shopping List: Generates a dynamic list of items to buy based on current inventory and expiry alerts.

- Expiry Notifications (planned): Reminds users to use items before they go bad to minimize food waste.

## 📲 Tech Stack
- Frontend: React — for audio recording UI and inventory display

- Backend: Python + FastAPI — for handling transcription, NLP parsing, and inventory logic

- APIs:

. Whisper (OpenAI) / Google Speech-to-Text — for voice transcription

. Perplexity Sonar — for natural language parsing of pantry data

. Database: SQLite (or any lightweight DB) for storing pantry inventory
 ## 📝 How It Works
1. User records a voice note describing pantry items and quantities.

2. Audio is transcribed to text via speech-to-text API.

3. Transcribed text is sent to Perplexity Sonar for semantic understanding — extracting item names, quantities, and expiry info.

4. Backend updates the pantry database accordingly.

5. User views updated inventory and shopping list through the UI.
   
## 🛠️ Setup & Run
Clone the repo:

```bash
git clone https://github.com/yourusername/audio-pantry-log.git
cd audio-pantry-log
```
Install dependencies:

```bash
pip install -r requirements.txt
Run backend server:
```

```bash
uvicorn app.main:app --reload
Start frontend:
```
```bash
cd frontend
npm install
npm start
```
Open http://localhost:3000 and start managing your pantry with your voice!

## 🔮Future Improvements
- Add barcode scanning for quick item input.

- Integrate voice assistants (Alexa, Google Assistant).

- Implement smart meal suggestions based on pantry content.

- Build mobile app for on-the-go access.

- Add push notifications for expiry reminders.

## 💭 Why Audio Pantry Log?
Managing a pantry manually is tedious and often inaccurate, leading to wasted food and money. Our app leverages voice convenience and AI-powered natural language understanding to make pantry management effortless, helping households save time and reduce waste — a small step towards a sustainable lifestyle.

## 🪪 License
MIT License





