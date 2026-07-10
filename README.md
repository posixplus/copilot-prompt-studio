# Copilot Prompt Studio

A free, single-file prompt builder for Microsoft 365 Copilot. Pick your task (document summary, meeting recap, follow-up email, or custom), set audience, length, and structure, and copy a precision-built prompt with accuracy guardrails that stop Copilot from inventing details.

**Live:** https://posixplus.github.io/copilot-prompt-studio/ (also at https://copilot-prompt-studio.netlify.app)

## Why

Copilot's summaries go wrong mostly because of vague prompts. This tool assembles prompts with explicit audience, length, output schema, and four accuracy rules: source-only grounding, "Not stated in the source" for gaps, verbatim figures, and section/page references.

## Tech

One self-contained `index.html`. No build, no dependencies, no data leaves the browser.
