# Text Transformation Suite

This project is a hands-on exploration of how to effectively communicate with large language models. I built a set of practical prompts to handle common text tasks, focusing on clarity and control rather than just hoping for a good output. It's about working smarter with AI, not harder.

## What I Built

### 1. Article Summarization
I wanted to see if I could get an AI to give me exactly the type of summary I needed, not just a generic one.
- **The Prompts:** [prompts/summarization.txt](./prompts/summarization.txt)
- **The Results:** [outputs/summarization.md](./outputs/summarization.md)

**What worked:** Simply telling the model "2-3 sentences" or "5-7 sentences" gave me drastically different outputs. Asking for an "analytical" summary versus a "concise" one fundamentally changed the tone and depth. It proved that clear, simple instructions are often the most powerful.

### 2. Technical Term Translation
My goal was to take complex technical terms and make them understandable for anyone. This is a real-world task for anyone explaining tech to non-technical teams or clients.
- **The Prompts:** [prompts/translation.txt](./prompts/translation.txt)
- **The Results:** [outputs/translation.md](./outputs/translation.md)

**What worked:** Giving the model just two or three clear examples was enough for it to understand the pattern perfectly. It consistently produced simple, accurate translations for new terms without any further help. This few-shot approach is incredibly reliable for structured tasks.

### 3. Audience-Specific Rewriting
I tested if a single, technical paragraph could be adapted for a complete beginner, an industry expert, and a marketing page without changing the core message.
- **The Prompts:** [prompts/rewriting.txt](./prompts/rewriting.txt)
- **The Results:** [outputs/rewriting.md](./outputs/rewriting.md)

**What worked:** The model's ability to infer the knowledge level of each audience was impressive. By just specifying the audience in the prompt, it adjusted word choice, sentence structure, and depth of explanation automatically. This turns a single piece of content into a versatile asset.

## What I Learned

This was less about coding and more about learning how these models think. The main takeaway is that precision beats volume. A well-designed, thoughtful prompt is far more effective than a long, complicated one.

The project demonstrates a practical understanding of:
- Getting good results from a model with no examples (zero-shot).
- Using examples to teach a model a specific format (few-shot).
- Directing output style, length, and tone through clear instruction.
- Tailoring content by defining who it's for directly in the prompt.

## How to Look Around

The `prompts` folder contains the exact text I used to instruct the models.\
The `outputs` folder shows the successful results, so you can see the direct connection between what I asked for and what I got.\
The `data` folder has the source text I used for the tasks.


## 📁 Project Structure
``` text-transformation-suite/
text-transformation-suite/
├── README.md # Contains the documentation
├── prompts/  # Contains the precise prompts used
├── outputs/ # Shows the successful results from various LLMs
└── data/ # Source materials used for the tasks