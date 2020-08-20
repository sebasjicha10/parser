# Parser

## Built with Python and nltk - Context-Free Grammar NLP
Program running: https://youtu.be/DsapUwxbJXI

## How to run

```
pip3 install -r requirements.txt
python parser.py
Sentence: Holmes sat.
        S
   _____|___
  NP        VP
  |         |
  N         V
  |         |
holmes     sat

Noun Phrase Chunks
holmes

```

AI to parse sentences and extract noun phrases.

This project uses the context-free grammar formalism to parse English sentences to determine their structure. 
