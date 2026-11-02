# NLP Portfolio · Hanniel Vinu A

My Natural Language Processing portfolio: the NLP systems I've built, my class work, and an in-browser NLP playground, set against a 3D scene of ancient scripts hanging on ropes.

**Live site:** https://hannielvinu.github.io/NLP-Portfolio/

## What's inside

| Section | What it shows |
|---|---|
| About | Who I am and the languages I work with |
| Class ledger | Stars, class interactions, case studies, homework, hands-on sessions and the course project |
| NLP projects | **Dobaara** (Hinglish intent + date extraction), **MoneyTrace** (multilingual speech + entity extraction + knowledge graph), **Setu** (barrier classification in the patient's language) |
| Playground | Unicode script detector, tokenizer, type/token ratio and bigrams; a Hinglish reply-intent parser |
| Pipeline | Course concepts (segmentation → classification), each linked to where I used it |
| Scripts | The 24 historical writing systems hanging in the background |

## Updating class work

All class entries live in the `CLASS_LOG` object near the top of the main `<script>` in `index.html`. Add an entry and the page renders it; empty lists show a placeholder.

## Tech

One static `index.html`: HTML, CSS, vanilla JS and Three.js (r128). Script fonts are Google Noto fonts, subset to only the glyphs used. Deployed with GitHub Pages via `.github/workflows/pages.yml`.
