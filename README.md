# pineapple-chatbot
**Very important: [see the chatbot manual](https://github.com/juan-aquino/pineapple-chatbot-manual) for all info on how to set up this project.**

A chatbot assistant for Cal State LA University.

This chatbot is able to collect text from the CSULA website page and organize/label this text into usable information (e.g. A faculty's name and email). Students can interact with the Chatbot to get common information retrieval service (e.g. staff and department info). The Chatbot consists of a front-end UI, a backend server chat program and database, a web crawler, a data abstracter, and a language understanding engine (Lex API).

The entirety of this project contains these programs:
- Dynamic chat website [w/ connection to Bot server] (React)
- Language Parser (Lex API)
  - understand user's intentions and get useful keywords
- Web Crawler
- Data Tagger and Organizer (spacy)
- Keyword Extractor (you must create your own MySQL database to store these keywords with their respective webpage link)

