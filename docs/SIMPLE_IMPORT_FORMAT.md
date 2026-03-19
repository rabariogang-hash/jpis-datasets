# SIMPLE IMPORT FORMAT

For the fastest possible JPIS data entry, use a small JSON manifest and keep long text in a separate `.md` or `.txt` file.

Supported convenience fields:

- `content_path` for law articles
- `full_text_path` and `anonymized_text_path` for court decisions
- `summary_path` and `excerpt_path` for legal literature

This lets you prepare data quickly, keep diffs readable in Git, and refine structure later.
