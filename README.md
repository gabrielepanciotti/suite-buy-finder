# BuyFinder

BuyFinder is a small, open-source starting point for a tool that helps people research items to buy. The repository currently provides the project metadata and publication-ready conventions; application features will be added in future releases.

## Features

- A minimal, framework-compatible project node configuration.
- Safe defaults for local configuration and public distribution.
- Continuous integration ready to run Python and Node.js suites when application code is added.

## Requirements

- Git
- Docker and Docker Compose (only when a compose setup is introduced)
- Python 3.13 and/or Node.js 20 (only when working on the corresponding application component)

## Quickstart

```bash
git clone https://github.com/your-account/buy-finder.git
cd buy-finder
cp .env.example .env
```

There is no backend, frontend, or Docker Compose service in this initial scaffold. Once a component is added, start it using its documented command, or run `docker compose up --build` when a compose file is present.

## Tests

This scaffold has no automated test suites yet. When Python tests are added, run `pytest`; when a frontend is added, run `npm ci && npm test && npm run build`. The CI workflow detects and runs those suites when their project files are present.

## Configuration

| Variable | Purpose |
| --- | --- |
| _None currently_ | The project does not require runtime environment variables yet. |

## License

Licensed under the [MIT License](LICENSE).
