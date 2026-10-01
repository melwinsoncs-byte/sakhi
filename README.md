# Sakhi 🌱

**A friendly first step to finding support.** Sakhi helps women who are new to digital services explore a useful government support starting point through simple text, tap-to-answer questions, or voice.

[Open the app](https://melwinsoncs-byte.github.io/sakhi/) · [View the source](https://github.com/melwinsoncs-byte/sakhi/blob/main/index.html)

## What it does

- Starts with three simple topics: farming, earning, and health or family support.
- Guides the user with one question at a time and large, clear answer buttons.
- Offers English, Hindi, and Bengali text, plus browser speech input and read-aloud controls where supported.
- Ends with practical next steps and local places to verify current scheme information.

## Demo and safety

Sakhi is a hackathon demo, not an official government service or eligibility checker. Scheme details and next steps are sample guidance and must be verified with a local government office. Sakhi does not request or store an OTP, PIN, password, or bank details. Answers remain in the browser session.

## Run locally

Open `index.html` in a modern browser. For voice input, allow microphone access when the browser asks. If speech recognition is unavailable, choose an answer or type instead.

## GitHub Pages

The repository includes a workflow at `.github/workflows/pages.yml` that publishes the static site from `main`. In the repository’s **Settings → Pages**, set **Build and deployment → Source** to **GitHub Actions**. After the initial setup, pushes to `main` trigger deployment.

## Future integrations

The demo keeps service guidance separate from any live government system, so verified scheme APIs or a trusted local help directory can be connected later without changing the guided interaction.