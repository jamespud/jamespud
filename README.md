# Hi

**Backend engineer** · Reliability, distributed systems & runtime infrastructure

Contributing to [bytedance/deer-flow](https://github.com/bytedance/deer-flow) across runtime reliability, persistence, sandbox infrastructure, CI, and security.

> I work on the failure paths — ownership, cancellation, durable state, fencing, and the cases where a timeout doesn't mean the work actually stopped.

## What I work on

In DeerFlow, an open-source agent harness, I've worked on:

* **Durable runtime correctness** — cancellation-safe MCP task claims with bounded compensation, lease-token fencing, and stale-generation rejection. ([#4966](https://github.com/bytedance/deer-flow/pull/4966))
* **Persistence & concurrency** — safe durable cleanup for thread deletion while fencing concurrent event writers. ([#5535](https://github.com/bytedance/deer-flow/pull/5535))
* **Sandbox reliability** — command deadlines, no-replay semantics, and session fencing for ambiguous AIO sandbox outcomes. ([#5634](https://github.com/bytedance/deer-flow/pull/5634))
* **CI infrastructure** — duration-aware parallel sharding for a 13k+ backend test suite with exactly-once coverage. ([#5137](https://github.com/bytedance/deer-flow/pull/5137))
* **Filesystem security** — Windows credential hardening against ACL inheritance, reparse points, hard links, and path races. ([#5141](https://github.com/bytedance/deer-flow/pull/5141))
* **Deployment infrastructure** — Gateway/provisioner state-root consistency for shared PVC-backed sandbox storage. ([#5625](https://github.com/bytedance/deer-flow/pull/5625))

My current focus is on **failure semantics and ownership boundaries in asynchronous and distributed systems**.

## Own projects

* **[tiny-store](https://github.com/jamespud/tiny-store)** — distributed commerce backend exploring inventory reservation, Redis atomic operations, idempotency, asynchronous persistence, compensation, and reconciliation.
* **[yahoo-stock-mcp](https://github.com/jamespud/yahoo-stock-mcp)** — MCP server for structured financial-market data access, focused on API boundaries, reliability, and caching.
* **[MAGI-system](https://github.com/jamespud/MAGI-system)** — experimental multi-agent system for agent orchestration and LLM application infrastructure.

📖 [Blog](https://jamespud.github.io/)
