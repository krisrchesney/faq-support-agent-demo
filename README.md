# FAQ support agent: showcase

A static page that replays recorded answers from a help-page chatbot: it answers customer questions
only from a company's public help pages, cites the page it used, and says "I don't know" with a link to
a contact page when the pages do not cover the question.

- **These are recordings, not a live bot.** GitHub Pages cannot run the bot, and nothing on the page
  calls a model, loads outside files or tracks visitors.
- **Two examples:** Brightwave, a made-up streaming service built only for testing, and the Missouri
  Department of Revenue's public help pages.
- **Not official.** The Missouri tab is an independent learning project. It is not affiliated with or
  endorsed by the State of Missouri, and its answers can be wrong. Check the cited page on dor.mo.gov.
  The State keeps its content rights; this repository holds no crawled page text.
- **Honest numbers.** The page lists the measured results with their caveats: small test sets written by
  the project, one run each, and a few failures shown on purpose.

The bot code and tests are not published yet. The page is one file, `index.html`.
