# FEP-35b7: Fediverse Servers, Instances, and Tenants

**Status:** DRAFT · **Type:** informational · **Author:** Steve Bate · **Received:** 2026-04-22

## Overview

This FEP defines terminology for describing Fediverse infrastructure, with the goal of
providing consistent vocabulary for specifications, implementations, and documentation.
It distinguishes three concepts that are often conflated in casual usage:

- **Server implementation** — a software codebase implementing one or more Fediverse protocols.
- **Server instance** — a specific deployment of a server implementation (configuration,
  storage, and an administrative boundary).
- **Tenant** — a logically and administratively distinct group of actors and data served by an
  instance, with isolated configuration, policies, and data.

The document is purely terminological: it does not prescribe a multitenancy model, routing
strategy, or deployment topology, but offers definitions that other FEPs can reference.

## Files

- [`fep-35b7.md`](fep-35b7.md) — the proposal

## The FEP

- Document: <https://github.com/steve-bate/fep-35b7-fediverse-terminology/blob/main/fep-35b7.md>
- Repository: <https://github.com/steve-bate/fep-35b7-fediverse-terminology>
- Discussion: <https://github.com/steve-bate/fep-35b7-fediverse-terminology/issues>

## License

This work is released under [CC0 1.0 Universal](LICENSE.md) (public domain dedication).
See [LICENSE.md](LICENSE.md).
