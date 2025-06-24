# Fileserver Indexer & Reporting Tool

This project indexes the contents of a file server and stores metadata (filename, path, size, last modified date, hash) in a SQLite database. A simple Flask web interface allows users to search for files, and duplicate detection/reporting is included.

## Features

-  Recursively scan file directories
-  Store metadata (filename, path, size, modified date, hash)
-  Detect and report duplicate files
-  Search via web interface (Flask)
-  Export results as CSV
-  Cron-ready for automation


