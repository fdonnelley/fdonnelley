# Finian Donnelley

CS student at UC Berkeley.

## Projects

### [XCeleration](https://github.com/XCelerationApp/XCeleration)
A race timing app for cross country and track, built with my twin brother in Flutter.
My league timed races with stopwatches and handwritten bib numbers, and my coach spent
hours after every meet matching numbers to names by hand. XCeleration replaced that, and
it's now on the App Store.

- Offline-first, with SQLite locally and Supabase sync
- Device-to-device transfer over a custom DATA/ACK/FIN protocol for courses with no service
- A computer vision pipeline that reads bib numbers written in Sharpie on runners' arms

### Chess Engine *(private)*
Started with Negamax, alpha-beta pruning, transposition tables, and a positional evaluation
function I wrote by hand. Later replaced the evaluation with a residual policy/value network
trained through self-play using a PPO-style actor-critic pipeline with Stockfish-guided
exploration.

### Felix *(private)*
A self-hosted personal AI system running on OpenClaw, connected to Slack, Google Workspace,
Todoist, GitHub, and the YouTube Data API through MCP servers. Most of the work went into the
safety layer: source-trust classification for external content, approval gates on sensitive
actions, and prompt injection defenses.

## Experience

**Balto Energy** — Software engineering intern, two summers. Built direct PG&E and Enphase
integrations from scratch, replacing a paid third-party dependency, and redesigned the
database schema to support multiple utilities and modeling runs per home.

**KDX** — AI and knowledge systems for an early-stage venture capital firm.

**One Intelligence** — Software engineering intern.

## Also here

[Hackathon_Climate_App](https://github.com/fdonnelley/Hackathon_Climate_App) is EcoMeter, a
carbon footprint calculator and chatbot built in a 12-hour hackathon that placed second out
of 15 teams. The other repos are older projects from high school.

## Contact

finian_donnelley@berkeley.edu
