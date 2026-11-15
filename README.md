# FatFIRE Spending Survey

An informal survey of what members of [r/fatFIRE](https://www.reddit.com/r/fatFIRE/) say they are worth, what they spend each year, and where the money goes: <https://matthewlloyd.github.io/fatfire-spending-survey/>

The page covers:

- the distribution of net worth and annual spend;
- how spending scales with net worth (typical spend at $5M, $10M, $20M and beyond) and how income changes it;
- spending categories such as housing, travel and kids, and how their shares shift with net worth;
- the net worth at which people report business class, second homes, household staff, private schools, private aviation and boats;
- how net worth changed for 274 people who reported it more than once, years apart, compared with the S&P 500 over the same dates;
- how spending compares with 622 households from the neighbouring r/ChubbyFIRE forum at the same net worth.

Charts, tables and summary figures can be filtered by single or married, kids or no kids, and working or retired.

## Data

The survey draws on 2,188 self-reported households from public r/fatFIRE posts and comments between 2016 and October 2026, collected through the [Arctic Shift](https://github.com/ArthurHeitmann/arctic_shift) Reddit archive. 1,041 of them give both a net worth and an annual spend. Language models extracted each author's own figures from the text; each Reddit account counts once. Every dollar figure is restated in 2026 dollars using the CPI-U for the year of the post.

The sample is self-selected and the extraction is imperfect. The page's **Method** section explains the sources, definitions and limitations in detail.

## Publishing

`public/index.html` is a single self-contained page: the data, charts and styles are inline, and only the IBM Plex fonts load from Google Fonts. The included `.github/workflows/pages.yml` workflow deploys `public/` to GitHub Pages on every push to `main`, or manually from the repository's **Actions** tab. In **Settings → Pages**, the source must be set to **GitHub Actions**.

## Copyright and reuse

Copyright © 2026 Matthew Lloyd. All rights reserved.

This repository is public so the survey and its methodology can be inspected and discussed. It is not open-source, and no permission is granted to copy, modify, redistribute, or use the page or its original presentation commercially without prior written permission. See [`RIGHTS.md`](RIGHTS.md) for the complete notice.

The underlying Reddit posts and comments are third-party content owned by their authors and are not licensed under this project's copyright notice. Household summaries on the page are paraphrases; each links to its source.
