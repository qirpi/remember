<img src="https://mem.cool/assets/remember1-4cc77497bf45b1d358f1c0d8fc3a5b1de567e4eefa2b4bd7bc3e0f8985acf8b5.png" width="400px"></img>

See all the stuff you ever highlighted from books and articles in one feed, with a spaced-repetition algorithm.

The goal is to help you remember (and hopefully apply) the most important knowledge you came across.

### Explore the context of annotations

Context matters. Clicking the highlight pops up the full paragraph where the it was made, and if you still need more context, there is a button to displays the lines before and after the paragraph (think `grep -C 1`).

Additionally, the book, the chapter (and subchapters if any) are displayed on each highlight's card.

My self-hosted Readwise alternative. Currently in PoC state, with only Calibre annotation import support.

### Roadmap
- [X] add book import feature with full text extract
- [X] import Calibre .opf and extract highlights from it
- [X] add PoC context features
- [X] rewrite context features (PoC implementation had some ..uhh.. caveats :))
- [X] convert html entities when importing epubs
- [ ] add spaced repetition
- [ ] add hypothes.is import features
- [ ] implement an adapter layer for easily adding annotation sources later
- [ ] write import adapters: kindle, ibooks, sioyek ..etc
