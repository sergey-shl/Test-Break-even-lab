# Break-even Lab
A responsive, dependency-free Business learning experiment for Year 12. Independent resource aligned to Cambridge International AS & A Level Business 9609 (2026–2028), section 5.4.4. Not endorsed by Cambridge or PBISS.

## Run
Open index.html directly, or run `python3 -m http.server 8080` in this directory. Link copying works best on localhost or HTTPS.

## Deploy with GitHub + Netlify
1. Create a GitHub repository and upload index.html, netlify.toml and this README.md to its root.
2. In Netlify, import the repository. Leave build command empty and publish directory as `.`. The included configuration sets this automatically.
3. Deploy and share the Netlify HTTPS address.
No installation, API key, backend or environment variables are required.

## Features
Live contribution, break-even, profit and margin of safety; accessible SVG chart; constrained profit challenge; prediction question with feedback; classroom view; share links that preserve settings; responsive dark interface; reduced-motion support. No analytics or student data collection in application code. Hosting providers may retain standard access logs.

## Calculation conventions
Break-even = fixed costs / (price − variable cost). With nonpositive contribution and positive fixed costs, no break-even exists. Displayed minimum whole cups rounds up. Margin of safety uses exact break-even output (and can be negative). All totals refer to one month. The chart shows 0–2,000 cups; an out-of-range break-even is disclosed. Sales and production are assumed equal. Price changes do not automatically change demand. Challenge accepts multiple solutions; for example price 85, variable cost 30, fixed costs 23,000, sales 600 yields profit 10,000.
