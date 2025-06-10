# 📝 Transition Phrase Extractor

This Streamlit app extracts structured transition phrase triplets from `.docx` files containing regional French news articles.

Each triplet is formatted as:

- **paragraph_a**: text before the transition
- **transition**: the linking phrase (e.g., "Dans un tout autre registre")
- **paragraph_b**: text after the transition

## 🔧 Installation

pip install streamlit python-docx

streamlit run transition_extractor.py
