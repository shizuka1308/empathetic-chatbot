# CSE635_NLP_Project
## Topic-Based Empathic Chatbot
● Developed an advanced chatbot system with natural, fluid conversations, leveraging NLU techniques and incorporating a the re-ranking mechanism for human-like content retrieval. 
● Integrated feedback analysis to adapt conversations based on user mood, ensuring personalized and seamless transitions.

## Setup

```
pip install -r requirement.txt
python -m spacy download en_core_web_lg
```
## Load IR knowledge base
```
#Download SimpleWiki dump from WikiMedia website and place in root directory
python wikibot/wikibot_loader.py
```

## How to Run
```
streamlit run app.py
```
[Link To Report](https://github.com/shizuka1308/empathetic-chatbot/tree/main/docs)
