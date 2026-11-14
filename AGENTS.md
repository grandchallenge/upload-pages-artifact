# Agent contract

**Engineering architecture and reliability:** Adopt [GCL-ENGINEERING-001 v1.0.0](https://github.com/grandchallenge/gcl-standards/blob/2a3cfed9419ba9b74eeaaee70b9db8c3f47f3c9b/standards/GCL-ENGINEERING-001.md), pinned at protected `gcl-standards` commit `2a3cfed9419ba9b74eeaaee70b9db8c3f47f3c9b`. Engineering agents own architecture, necessity, integration, tests, deploy/readback and retirement; reuse GitHub and existing components before inventing infrastructure. Do not duplicate workflow authority or mistake CI/merge for live completion. Preserve this repository's superior, reserved, and domain-specific policies. Cross-repository adoption requires explicit readback, never assumption.

This repository is a Provider-profile fork. Preserve upstream behavior, pin
every external Action to a full commit SHA, and make changes through pull
requests. Under `GCL-AGENT-STAFFING-001` version `1.0.0`, one Codex system may
staff distinct non-reserved logical passes, merge through satisfied protected
controls, and read back the result. Automation may not certify a claim,
manufacture reserved authority, or push directly to a protected branch. A
third-party Action must also be named in the organization allowlist; a SHA pin
alone does not authorize it.
