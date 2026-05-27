# AI Mentor Bootcamp — Mounika Jalem
## Day 1A — Setup complete

- ✅ Google AI Studio API key provisioned
- ✅ Groq API key provisioned
- ✅ Hello-Gemini call working — see [Day1_Setup.ipynb](Day1_Setup.ipynb)
- 4-tool comparison matrix from Lab 1A: see screenshot below
## Day 1B — Setup complete

- ✅ Google AI Studio API key provisioned
- ✅ Groq API key provisioned
- ✅ Hello-Gemini call working — see [Day1_Setup.ipynb](Day1_Setup.ipynb)

![Gemini first call](gemini_first_call.png)
## Day 2 Lab 2B — Errors handled

1. Markdown fence wrapping
   Retry prompt forces raw JSON output.

2. Missing phone number
   Optional[str] = None allows validation.

3. Empty input
   Empty strings are caught before Gemini API call.

## Sample resumes processed: 3 / 3 successful

Local time: 12.54s
[POSITIVE 1.00] I really enjoyed working on the team and shipped 3 features.
[NEGATIVE 1.00] I was the only one writing code; everyone else was slow.
[POSITIVE 1.00] I learned a lot from my mentor and grew technically.
[NEGATIVE 1.00] I had to redo most of my teammate's work because it was wron
[POSITIVE 1.00] My internship was great — would recommend it to anyone.
API:   min A0.8s | avg 1.2s
Local: min 0.93s | avg 1.14s>



## Reflection

Semantic search returns the nearest semantic match,
not necessarily the correct factual answer.

Embeddings group related topics together in vector space.
PCA visualization helped show semantic clustering.
