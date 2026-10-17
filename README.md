# Joy's Vocabulary

Live site: https://feverpitch15.github.io/Joys-Vocas/

The home page links to the child practice page and parent reference page. GitHub Pages publishes from the `main` branch root, so the public site is updated at the same URL whenever changes are pushed to `main`.

## Weekly update workflow

1. **Worksheet Detection**: Check `nonfiction/IMG_*.{jpg,JPG,jpeg,JPEG}` for the latest vocabulary practice worksheet (Unit and 10 words).
2. **Text & Content Extraction**:
   - Extract 10 words, parts of speech, textbook definitions (Book meaning), worksheet fill-in-the-blank examples, and child-friendly Korean explanations (Parent tips).
3. **5×2 Sprite Sheet Illustration Generation**:
   - Generate a 16:9 landscape 5×2 grid (10 panels) illustration sheet matching the 10 words in order (Top: 1~5, Bottom: 6~10).
   - Style: Clean 2D storybook style, no text/labels, equal rectangular panels.
   - Save/replace at `nonfiction/images/Gemini_Generated_Image_ubono3ubono3ubon.png`.
4. **Update Vocabulary Pages**:
   - `nonfiction/tuesday_word_cards_child.html`: Update Unit number and the `words` array (10 items).
   - `nonfiction/tuesday_word_cards.html`: Update Unit number and the 10 card details.
5. **Privacy & Deployment**:
   - Ensure source worksheet photos are excluded by `.gitignore`.
   - Push to `main`; GitHub Pages redeploys automatically to https://feverpitch15.github.io/Joys-Vocas/.

Worksheet photos named `IMG_*.JPG`, `IMG_*.jpg`, or `IMG_*.jpeg` directly inside `nonfiction` are excluded by `.gitignore`. Do not force-add them. The site and repository are public; only publish the vocabulary pages and generated illustrations, not source worksheet photos or personal information.

