# unierp-corporate-site-template

**Layer L4 — Presentation** of the [UniERP](../unierp-platform) platform.
Depends on: the design system.

## What this is

The starter template a tenant's public website is generated from.

## The invariant this repository owns

Rendered by the schema-driven runtime, so a tenant site and a first-party page share one renderer.

## The rule that applies everywhere

A repository may depend only on published artifacts of a **strictly lower
layer** — never sideways within a layer, never upward. A cycle is not
discouraged; it is unrepresentable, because the lower layer's package cannot
name the higher one.

See the [platform overview](../unierp-platform/README.md) for the full map, and
[`PLATFORM_ARCHITECTURE.md`](../ERPSys/docs/PLATFORM_ARCHITECTURE.md) § 4.2 for
the reasoning.

## Licence

AGPL-3.0.
