---
"agent-browser": patch
---

Allow null values for the screenshot selector option. Previously passing an explicit null for the selector field would fail validation, now it is properly accepted alongside undefined.
