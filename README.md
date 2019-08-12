# Guardian article extractor

About 15 years ago I wrote a script to scrape the Guardian newspaper site
and write them to a .html so that I could print it off for reading in the
toilet at work.

This took a couple of weeks to get working correctly. Then they had a
couple of modifications and I had to rewrite but it wasn't so hard.

---

### Steps in the procedure

1. Scrape the front page and get the links to stories
1. Access the links and scrape each of the pages
1. Extract meta data and story text from the pages
1. Sort and create table of contents (toc)
1. Format and dump to a file

### Much easier

Things are easier today using **Goose**.
