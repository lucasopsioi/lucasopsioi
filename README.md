# lucasopsioi

**I build AI products for enterprise operations — in the field, not the lab.**

Channel-sales category lead in consumer electronics (Latin America): pricing approvals, demand & inventory planning, sell-out analytics across a dozen countries. Every repo here started as one of my own team's weekly pains and shipped as a working product — then got measured, hardened and iterated like one.

> **Educational use only.** Everything here is published for learning and demonstration. Commercial use is not permitted; anyone considering commercial use is solely responsible for legal and regulatory compliance in every applicable jurisdiction.

## What's here

| Project | One-liner |
|---|---|
| **[salesboard](https://github.com/lucasopsioi/salesboard)** | AI analyst over 15 channel-sales boards: 9 domain-expert agents, read-only tool calling, and a **code-level provenance gate** — any number the model can't trace to a real query is blocked, not warned. 120+ releases. |
| **[latam-price-intel](https://github.com/lucasopsioi/latam-price-intel)** | Resident multi-agent pipeline: public retail listings in 6 countries → LLM cleaning with an audit harness → matched price boards + daily Telegram briefing. |
| **[psi-simulator](https://github.com/lucasopsioi/psi-simulator)** | Single-file sell-in/sell-out/inventory simulator with replenishment & rounding rules. Zero-install, field-ready. |
| **[pptx-to-ai-text](https://github.com/lucasopsioi/pptx-to-ai-text)** | Decks → position-aware structured text, so LLMs reproduce layout instead of hallucinating it. |
| **[doc-to-ai-text](https://github.com/lucasopsioi/doc-to-ai-text)** | Same idea for PDFs and Outlook mail. |

## How I work

**Evaluation before vibes.** The flagship ships a 30-question golden set with severity grading (a fabricated number is a red line; an honest "not in the data" is not). Eval-driven iteration took answer accuracy **15% → 95%** and red-line failures **11 → 0** — every run human-reviewed, and the zero-red-line result holds across models from two different vendors — not with better prompts, but with mechanisms: dimension-validated tool inputs, tool-side arithmetic, and a provenance gate on every number in the answer.

**Trust is a product feature.** Dual runtime (cloud API or fully on-device open-source models) because the users I build for won't paste sensitive data into a cloud model — an AI tool nobody dares to use has zero accuracy by definition.

---
*All projects: personal work, personal equipment, no employer code or data; demo datasets are fictional and reproducible from fixed seeds.*
