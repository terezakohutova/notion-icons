# notion-icons

Portrait icons for the Claude Code agents in my workspace. Each agent has a
persona named after a historical figure, and each PNG here is that figure's
portrait, cropped to a circle and toned sepia. They live in a public repo only
so Notion can load them as page icons by URL.

## Using them

Point Notion (or anything else that takes an image URL) at the raw file:

```
https://raw.githubusercontent.com/terezakohutova/notion-icons/main/<agent>.png
```

for example `.../main/google-ads.png`. The file name is the agent's slug, so a
new agent needs a new PNG with its slug before its Notion card can show it.

## Where the images come from

Every portrait starts as the lead image of the person's Wikipedia article
(cs or en Wikipedia, via the MediaWiki API), then is cropped and toned for this
set. The originals are historical portraits hosted on Wikimedia Commons; each
one's licence is on its Commons file page and has not been re-checked file by
file here. None of the images are AI generated.
