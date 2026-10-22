# MGM Studio – VI/EN layout update

- All marketing pages retain `/` (Vietnamese) and `/en/` (English) routes.
- The language selector sits at the upper-right of each page banner, not below the banner.
- `/privacy/{app}/` shows Vietnamese only; `/en/privacy/{app}/` shows English only. The latest Vietnamese source page supplied both language bodies and was used for the split, avoiding older duplicate English pages.
- The duplicated title block in Chanting Counter privacy pages was removed.
- Privacy texts were **not legally reviewed or fact-checked**; verify that they match each application's actual handling of user data before publication.
- `hreflang`, canonical URLs, and sitemap entries were updated for split policy pages.
- HTML was formatted with indentation and line breaks; no HTML minification. Shared images, CSS and JavaScript behavior are retained.
- Firebase deploy from repo root: `firebase deploy --only hosting:mgm --project mgm-studios`.
