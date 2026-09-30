# Blades AI — Transformers Edition

This is a fan-made Transformers information website.

## Google search
The site supports Google's Custom Search JSON API. Google requires:
- an API key
- a Programmable Search Engine ID (`cx`)

For a real public deployment, do NOT put a secret API key in browser JavaScript. Put the Google request behind your own server/proxy and keep credentials there.

Google's current documentation says the Custom Search JSON API requires a configured Programmable Search Engine and API key. It also notes the API is closed to new customers and existing customers are scheduled to transition by January 1, 2027.

## Run
Open `index.html` locally, or host the folder on a static web server.

Without API configuration, the Search Google button opens the query directly on Google.
