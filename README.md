# Spell It! — Speaking Spelling Quiz

A simple, mobile-friendly, no-build spelling quiz for the exact 20 words in [SPELLING_WORDS.md](SPELLING_WORDS.md).

## Play

Open `index.html` on a hosted HTTPS website, tap **Let's start!**, and listen for a word. Spell it aloud with **Speak letters**, enter it with the keyboard, or use **Tap A–Z letters instead**.

The quiz:
- Shuffles the same 20 words each new session.
- Says each word aloud, without displaying its spelling up front.
- Asks the child to review letters recognized from their voice before checking.
- Lets the child hear a word again or start the current word over without penalty.
- Moves missed words into another round until every word has been spelled correctly.
- Saves in-progress quiz state locally in the current browser (localStorage).

**Speech recognition is browser-dependent.** On iPhones, use Safari and grant microphone permission if supported. If speech recognition is unavailable or mishears individual letters, use typing or the on-screen letter buttons instead. On-screen answer checking is exact; it does not use a language model or generate new words.

## Publish with GitHub Pages

1. Open the [repository Settings → Pages](https://github.com/zadams/spelling-quiz/settings/pages).
2. Under **Build and deployment → Source**, select **Deploy from a branch**.
3. Select branch **main**, folder **/(root)**, and press **Save**.
4. Wait for GitHub to publish, then open **https://zadams.github.io/spelling-quiz/**.

You can share that HTTPS address with your child. GitHub Pages hosting is public, so don't add private information to this repository.

No dependencies or build process are required. All application code lives in `index.html`.
