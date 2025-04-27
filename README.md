# MedPal - One Stop Solution For healthcare
<p align="center">
  <img src="https://github.com/Anshi-Khandelwal/MedPal/blob/main/MedPal%20logo.png" alt="MedPal Logo" width="150"/>
</p>

# 🩺 MedPal - Your Smart Healthcare Assistant

MedPal is a generative AI-powered healthcare assistant that answers medical questions, suggests home remedies, assesses symptom severity, and recommends nearby clinics based on user input.

Built using:
- **Fine-Tuned FLAN-T5 model**
- **Retrieval-Augmented Generation (RAG) with Weaviate**
- **Prompt Engineering & Synthetic Data Generation**
- **Streamlit UI (coming soon!)**

---

## 🚀 Features

- 📚 **Knowledge Retrieval**: Retrieves answers from a curated medical knowledge base using RAG.
- 💊 **Health Advice**: Suggests medicines or home remedies for common conditions.
- 🚑 **Severity Assessment**: Scores user symptoms from 1 to 5 based on urgency.
- 🏥 **Nearby Clinics**: Suggests real-world doctors and clinics if symptoms are serious.
- 🔁 **Smart Follow-Up**: Recommends related questions the user might also ask.

---

## 🛠️ Technologies Used

- Python 🐍
- Hugging Face Transformers 🤗
- Sentence Transformers (MiniLM)
- Weaviate Vector Database
- Streamlit (for app deployment)
- Hugging Face Spaces (for hosting)

---

## 📦 Installation

# Clone the repository
git clone https://github.com/your-username/medpal-healthbot.git
cd medpal-healthbot

# Install dependencies
pip install -r requirements.txt

🎯 How to Use
Open the Streamlit app (or Colab for manual testing).

Enter your health-related question.

MedPal will generate an intelligent, safe answer.

If severity is high, you'll be asked for your ZIP code to find nearby clinics!

--
## 📄 Project Structure
medpal-healthbot/
│
├── medpal.py          # Core healthbot logic (fine-tuned + RAG)
├── app.py             # Streamlit/Gradio app script
├── requirements.txt   # Required Python libraries
├── README.md          # Project documentation
