# Data journalism portfolio

A one-page, traditional newspaper-inspired portfolio template. It includes a blackletter masthead, a lead story, project case studies, a filterable clips archive, a skills section, biography, contact details, and a downloadable sample résumé.

## Preview

Run `npm start`, then open http://127.0.0.1:4173. No dependency installation or build is required. The preview server requires Node.js.

## Personalize

- Edit `site/dist/index.html` for the journalist's name, biography, contact address, project headlines, and clip metadata.
- Edit `site/dist/styles.css` for typography and layout.
- Edit `site/dist/script.js` for project previews, contributions, methodologies, and illustrative data. Update the clipboard address there too.
- Replace `site/dist/sample-resume.txt` with your résumé and update its link in the page.
- For real clips, replace the sample preview buttons with links to published articles. Include the title, publication, date, and your contribution. Add methodology and code links where available.

All stories, publications, biographical details, résumé details, and datasets are fictional examples. The charts display illustrative data and must be replaced before presenting them as journalism.

## Images and fonts

City photograph: [Damian Kravchuk on Unsplash](https://unsplash.com/photos/new-york-city-street-scene-with-classic-buildings-QGkJTWTA7Ew).
Subway photograph: [Pascal Bernardon on Unsplash](https://unsplash.com/photos/people-standing-in-subway-station-d5vX_IjSNVw/).
Both photographs are used under the [Unsplash License](https://unsplash.com/license). They are displayed as illustrative imagery and do not document the fictional stories.

Google Fonts supplies UnifrakturMaguntia, Libre Caslon Display, Libre Caslon Text, and DM Sans. Local system fonts provide fallbacks if fonts cannot be loaded. Photos require an internet connection.

## Verification

`npm run check` verifies JavaScript syntax. The template is responsive and uses semantic section headings, accessible filter states, native modal keyboard behavior, reduced-motion support, and a print stylesheet.

