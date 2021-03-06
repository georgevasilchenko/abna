# ABN Amro mutations retrieval

This Python library enables retrieval of mutations from the Dutch ABN Amro
banking site using the "soft token" (5-digit pass code).

Requirements:

- Python 2.7 or 3 (tested with 3.5)
- requests (tested with 2.15.1)
- cryptography (tested with 1.4)

## Alternatives

[abnamro-tx](https://github.com/mkrcah/abnamro-tx) is a docker-based solution
to run a headless Chrome instance that can download mutation files for you.
