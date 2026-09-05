# Rosetta Stone Builder

An interactive page for service-based business leaders to build their organizational "spine": the shared context that stops a team (and its AI tools) drifting into different versions of reality.

Hosted on Vercel. Single static `index.html`, no backend, nothing stored on a server.

## What it does

Guides the client through seven sections, one at a time:

1. **What we do and refuse to do** — boundaries and core work
2. **The customer** — who you serve and what drives them
3. **Offers and pricing** — what you sell and what it costs
4. **Voice** — how the company sounds
5. **The framework** — methodology and approach
6. **Brand and design** — the visual identity
7. **Ways of working** — how decisions flow and escalate

Then a Finish step with:

- **Print / Save as PDF** — a clean, print-formatted document (cover with company name and date, one heading per section, "Be Limitless. Be Bold." footer). The browser's print dialog handles "Save as PDF".
- **Copy as text** — the whole Rosetta Stone as markdown, ready to paste into a ChatGPT / Claude / Gemini project or a shared doc.
- A read-through of the full document, and a checklist of which sections are still blank.

## Privacy

Nothing is uploaded or saved on a server. Answers are kept in the visitor's own browser (localStorage) so a refresh doesn't lose their work; "Start over" clears them. There is no login, no gate, and no email capture.

## Deploying

Push to `main` and Vercel redeploys automatically. No build step.

---

Built from *The Office Stack Build* by Peter Swain Inc / Lizzie Swain
Adapted for Limited to Limitless clients
