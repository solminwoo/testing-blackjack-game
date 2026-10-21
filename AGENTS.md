# testing-blackjack-game engineering guidance

<!-- ecc-engineering-defaults:start -->
## Engineering defaults
For coding work, read [.engineering/defaults.md](.engineering/defaults.md).
These are shared fallback conventions; the existing project owner, nested instructions,
skills, model choices, domain contracts and stronger verification/release gates remain authoritative.
No hooks, permissions, MCP services or background automation are installed by this guidance.

### Project adaptation
Java 11 Maven/Spring Boot test project with JUnit 4. Candidate check: `./mvnw test` (Windows: `.\mvnw.cmd test`). Inspect existing fixtures, keep game behavior deterministic, and preserve wrapper/dependency versions.
<!-- ecc-engineering-defaults:end -->
