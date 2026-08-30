# Financial Change Check — Prolific-ready hosting package

Upload these files to the ROOT of the GitHub repository:
- index.html
- config.js
- README.md

This package is ready for HTTPS hosting, but NOT yet ready for paid participants.

Before launch:
1. Connect a secure response endpoint and put its HTTPS URL in `config.js`.
2. Put the Prolific completion redirect URL in `config.js`.
3. Test with a URL containing:
   ?PROLIFIC_PID=test123&STUDY_ID=test-study&SESSION_ID=test-session
4. Confirm a test response appears in your response database.
5. Confirm completion redirects back to Prolific.

Never put API keys, passwords, database secrets, or private tokens into this public repository.
The browser should only contain a public submission endpoint designed to accept study responses.
