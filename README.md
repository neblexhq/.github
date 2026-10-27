## Neblex

Neblex Integration Fabric is an AI-native integration platform (iPaaS) for building flows, AI agents, apps and forms that connect SaaS applications, databases and on-premises systems. It was built for AI from the start: you can design, test and run integrations from an AI client through the Neblex MCP server, or in the visual builder.

Flows and AI agents run in the Neblex cloud or on an on-premises runtime inside your own network. The runtime is a single Rust binary with no dependencies, so records from internal systems can be processed where they live.

### What it does

- Workflow automation and data integration between SaaS apps, databases, file stores and message brokers
- Data quality inside the flow, before a record lands: validation checks, fuzzy deduplication (Jaro-Winkler, edit distance, Soundex), normalization, lookup enrichment and human review with SLAs
- AI agents with tools that act on real systems, with knowledge and memory kept in a vector store you own
- Bulk data processing, change data capture and warehouse loading
- Replay a failed run from the step that failed, with a log of every run

### Repositories

- [neblex-mcp](https://github.com/neblexhq/neblex-mcp): remote MCP server for Claude Code, Cursor, Codex, VS Code and other MCP clients. Listed in the official MCP Registry as `io.github.neblexhq/neblex`.

### Links

- Product: [neblex.com/integration-fabric](https://www.neblex.com/integration-fabric)
- Capabilities: [neblex.com/integration-fabric/capabilities](https://www.neblex.com/integration-fabric/capabilities)
- MCP documentation: [neblex.com/integration-fabric/docs/guide/mcp](https://www.neblex.com/integration-fabric/docs/guide/mcp)
- Blog: [neblex.com/blog](https://www.neblex.com/blog)
- Pricing: [neblex.com/integration-fabric/pricing](https://www.neblex.com/integration-fabric/pricing)
