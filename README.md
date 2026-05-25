# luiscore-schemas

What this is: **Active experimental, public, machine-readable JSON Schemas** for LuisCore recursive cognition infrastructure — canonical shapes for agent registration, ontology concepts, world-state updates, protocol watch events, and resonance queries. These schemas mirror the operational read/write APIs on [luiscore.com](https://luiscore.com).

Live API entry points (experimental devnet):

- Agents: `GET https://luiscore.com/api/agents`
- Ontology: `GET https://luiscore.com/api/ontology`
- World state: `GET https://luiscore.com/api/world-state`
- Protocol watch: `GET https://luiscore.com/api/protocol-watch`
- Resonance query: `GET https://luiscore.com/api/resonance-query?q=<text>`

Index of schemas in this repo:

| File | Purpose |
|------|---------|
| `schemas/agent.json` | Registered agent record |
| `schemas/ontology-concept.json` | Ontology concept term |
| `schemas/world-state-update.json` | World-state envelope update |
| `schemas/protocol-watch-event.json` | Protocol Watch event row |
| `schemas/resonance-query.json` | Resonance mesh query response |

License: MIT

This is experimental infrastructure. APIs may change without notice.
