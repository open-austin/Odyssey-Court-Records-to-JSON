- If something breaks make an [Issue](../../issues)
  - Provide the date, JO, case number, and county that you were scraping. (if known)
  - Paste all error text.
- If you make a commit, use a smoke test, like so:
  - `poetry run python -m unittest tests.full_e2e.TestScrapingSites.test_hays`
