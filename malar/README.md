# Malar — Malayalam, little by little

A standalone, colorful Malayalam learning web app. All application code, styles, and learning content are in `index.html`. No build tools, API keys, or external libraries are required.

## Make it a website with GitHub Pages

1. Open this repository’s **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Choose **main** and **/(root)**, then **Save**.
4. Wait for GitHub’s deployment to finish and open the website link shown in Pages. The root page redirects to the Malar app in `/malar/`.

You can also copy `malar/index.html` into the root of another repository, naming it `index.html`, and enable GitHub Pages there. To preview locally, download `index.html` and open it in a browser; browser-local storage behavior for `file:` URLs can vary, so use a hosted page for consistent saved progress.

## Included

- 12 starter letters, with finger/stylus/mouse drawing, undo, clear, and hideable shape guides.
- Keyboard alternative to freehand drawing.
- Four grammar lessons with examples, practice questions, and feedback.
- Six everyday word cards with reveal controls and reviewed markers.
- Optional Malayalam browser speech when a matching voice is available.
- Saved progress and pronunciation-guide preference using localStorage.
- Responsive layout, keyboard controls, language attributes, labeled inputs, status announcements, reduced-motion support, and scalable text.

## Scope and data

This is a starter, not a full alphabet or complete course. Shape guides do not teach stroke order, and drawing is self-checked rather than graded. Romanization is approximate; a Malayalam educator should review content before public educational release.

No account, ads, or analytics. Progress stays in the current browser and does not sync. Drawings are discarded on navigation. Optional pronunciation uses the browser’s speech service; voice processing and availability depend on the device/provider. If browser storage is blocked, progress lasts only for the current visit.

## Validation

JavaScript syntax checked with Node. Browser-checked: navigation, correct/incorrect grammar feedback, keyboard letter practice, freehand drawing, completion persistence after reload, word reveal and review, pronunciation-guide toggle, and reset cancellation. Full mobile-device, assistive-technology, and Malayalam-voice testing remain outstanding.

Grammar reference: https://universaldependencies.org/ml/
GitHub Pages instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
