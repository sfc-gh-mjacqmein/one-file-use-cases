# One-File Use Cases

A catalog of single-file Snowflake use cases. Each one is one `.sql` file you can open in a
Snowsight worksheet, read, run, and undo. Select a database and warehouse, run the complete
file unchanged, and open `OPEN_APP_URL` from the final result: it discovers the account it is
pointed at, shows what it builds and what that costs, and installs the app. Production actions
stay behind their own approval. Every one ships a `TEARDOWN()`.

**Open the catalog:** https://sfc-gh-mjacqmein.github.io/one-file-use-cases/

This repository contains the client-facing catalog, its images, the offline HTML,
and generated SQL installer downloads. Readable development source lives elsewhere.

Streamlit installers use one expand-icon menu for App only and Show Snowsight.
Each choice opens a new tab and leaves the original session intact. The catalogue
does not claim that fixture UI checks establish backend or production readiness.
