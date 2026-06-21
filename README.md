# curator 

A 30-day, hands-on data curation skill-build — sourcing, cleaning, deduplicating, filtering, annotating, and publishing real datasets, end to end.

## Why this repo exists
Built to learn the full data curation pipeline used in production AI/ML data teams — from raw data acquisition to a publish-ready, documented dataset.

## Structure

| Folder | Week | Focus | Output |
|---|---|---|---|
| `week0-python-foundations/` | 0 | Python + regex fundamentals | CSV filter script |
| `week1-data-manipulation/` | 1 | Pandas, JSONL/Parquet, HF Datasets, data cleaning | Mini curation pipeline |
| `week2-data-acquisition/` | 2 | BeautifulSoup, Scrapy, APIs, Common Crawl | 500+ doc raw corpus |
| `week3-quality-filtering/` | 3 | Dedup (MinHash/LSH), heuristic + semantic filtering, contamination checks | Quality-filtered corpus v2 |
| `week4-annotation-capstone/` | 4 | Label Studio annotation, reproducible pipelines, final dataset | Published HF Hub dataset |

Each week folder contains:
- `scripts/` — working code for that week's checkpoints
- `notes.md` — what I learned, decisions made, problems hit
- `output/` — sample data produced (or link to HF Hub if too large)

## Tech stack
Python · pandas · Hugging Face `datasets` · Scrapy · BeautifulSoup · datasketch (MinHash/LSH) · FAISS · Label Studio

## Setup
\`\`\`bash
python -m venv venv

source venv/bin/activate

pip install -r requirements.txt
\`\`\`

## Final capstone
End-to-end curated dataset published on Hugging Face Hub: [link once live]

## Status
🟡 In progress — Week 0 of 4