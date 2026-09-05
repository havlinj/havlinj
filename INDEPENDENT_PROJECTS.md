# Independent Projects

*Written 2026-09-05.*

### Exploratory, Self-Directed Engineering

These three projects have had a particular purpose right from the start:

They were meant to give me hands-on experience with technologies I hadn't worked with before but was genuinely curious about. Only one of them—the website—had a different primary purpose. I designed the others to immerse myself in whatever I wanted to practice. With projects of my own, I could move freely, never depending on anybody else's decisions, and slow down whenever something needed more time to sink in.

Sometime in the first half of 2026, I changed my mind about AI tools. My first agentic workflows; the shock of realizing how ridiculously powerful they could be; some uneasy thinking about what that might mean for my career; eventually shaking that off; then days of experimenting with the process to see what would fit me best. What I eventually settled on was simple: cut friction and routine work, keep the judgment, and spend the freed attention on design, reasoning, and clarity.

**The resulting software remains public for anyone who wants to inspect my engineering work.** The authorship is unusually clear: I drove the architecture, implementation, tests, infrastructure, and delivery—and enjoyed tackling each.

One distinction is worth making explicit: I never expected any of these projects to attract users, contributors, popularity, or a community around them. They have little to do with the community-driven OSS model. I very much like what OSS makes possible and the dynamics of projects that grow that way—but these were never meant to go in that direction.

Nobody else depended on them, yet I never lowered the bar just to make things easier on myself. No "it's only a side project" shortcuts. I held them to standards I'd expect from production software and deliberately kept the work demanding enough to learn from.

They are built as real software, not demos. If anybody ends up using them, great—but I'm not naive about it. The web is full of software that never finds users.

### Projects

- **[Blockchain Governance Platform](https://github.com/havlinj/chain-to-cloud-ingestion)** — Ongoing exploration of a distributed system integrating on-chain governance workflows with cloud-native event processing, messaging, and analytics across AWS and GCP.
  - **Implemented:** Solana (Anchor, Rust, commit-reveal, Merkle allowlist); AWS operational pipeline (TypeScript ingestion, Go aggregator, SNS/SQS, Lambda, DynamoDB, Terraform)
  - **Planned:** gRPC read API; GCP (Pub/Sub, BigQuery, analytics); Kafka; Grafana; Phoenix LiveView

- **[Feature Flag API](https://github.com/havlinj/featureflag-api)** — GraphQL API for feature flags and A/B experiments, with JWT RBAC, deterministic percentage and attribute-based rollout, and fail-closed audit logging.
  - Go, GraphQL, PostgreSQL

- **[Personal Website](https://github.com/havlinj/havlinj.github.io)** — Personal website and writing platform.
  - TypeScript, Astro, Playwright
