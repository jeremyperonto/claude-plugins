---
type: llm
weight: 3
focus: trace
---

PASS if every claim about the page (screenshots, ratings, review text, price) is supported by fetched content, and anything that couldn't be seen (e.g. screenshots not rendered in a text fetch) is named as a gap.
FAIL if it describes screenshots, ratings, or reviews it never retrieved.
