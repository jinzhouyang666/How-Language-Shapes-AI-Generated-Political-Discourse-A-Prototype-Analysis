# How Language Shapes AI-Generated Political Discourse: A Prototype Analysis in English vs. Dutch

This project explores how language shapes ChatGPT's framing of political corruption topics. It compares responses to identical prompts in English and Dutch, using sentiment and framing analysis to uncover potential asymmetries in tone, empathy, and mobilization language.

## Research Motivation

As generative AI tools like ChatGPT become part of political dialogue, we still know little about how users interact with them on sensitive issues like **corruption**, or how these models **frame such topics across languages**.

> This prototype experiment supports the broader project:  
> "Talking Politics with Artificial Intelligence".

## Research Questions
- Does ChatGPT generate **different political sentiment or framing** depending on the prompt's language?
- Are Dutch responses more **neutral, institutional, or factual** than English ones?
- Does AI subtly shift emotional tone and civic agency framing across languages?

## Experimental Design

| Element            | Description                                 |
|--------------------|---------------------------------------------|
| Prompts            | 7 paired prompts in English & Dutch         |
| Topics             | Corruption, civic action, AI disinformation |
| Model              | GPT-4 Omni (default settings)              |
| Categories         | A – Systemic framing<br>B – Civic action<br>C – AI misuse<br>D – Cultural views |
| Tools              | `TextBlob` (English) + `DutchSentimentAnalysis` (R) |
| Responses          | Automatically generated, no manual edits    |

## Key Findings

- English answers showed higher emotional variance (positive and negative polarity).
- Dutch responses were more often neutral, fact-focused, or system-oriented.
- Notable divergences appeared in prompts involving:
  - Empowerment (Dutch B2: +0.43 vs English B1: -0.13)
  - System trust (Dutch A4: +0.63 vs English A3: +0.08)
- Dutch outputs used more empathetic language in some cases, but avoided overt critique or alarmism.

## Limitations

- Small sample (n = 14 responses), exploratory by design
- Single output per prompt, no prompt engineering or regeneration
- Sentiment tools vary by language; results are not directly symmetrical

## Next Steps

This prototype lays the foundation for:

- Larger-scale surveys of GenAI use in political contexts
- Behavioral experiments measuring opinion shift or trust after exposure
- Model comparison (GPT-4 vs Claude vs open-source LLMs)


