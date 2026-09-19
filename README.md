# Ausca Document OCR field test

This repository preserves the public, redacted evidence for one independent paid `document.ocr` invocation completed for Frantic bounty #131.

The test input is a genuine scanned public-domain page from O. Henry's *The Four Million*:

- Source page: https://commons.wikimedia.org/wiki/File:FourMillion16.png
- Original file: https://upload.wikimedia.org/wikipedia/commons/9/9f/FourMillion16.png
- Test derivative: original scan converted locally to a 1200 px-wide JPEG with ffmpeg quality 3
- Media type: `image/jpeg`
- Size: `232,395` bytes
- Local SHA-256: `d6d8bad0aff72a74e0454a3ee7bf99c8c48c8e83eeb3570df1e52b24ec6d76eb`
- Rights: public domain, as stated on the Wikimedia Commons file page

After the one authorized run, this repository will contain:

- `evidence.json` — machine-readable timings, identifiers, payment terms, validation results, and redacted request/response facts.
- `report.md` — the chronological human-readable field report, including specific issues and an actionable recommendation.

Private keys, bearer tokens, payment signatures, document bytes, and unredacted credentials are never published here.
