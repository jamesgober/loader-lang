# loader-lang - Roadmap

> Path from scaffold to a stable 1.0. Hard parts are front-loaded; each phase has hard exit criteria.
>
> **Anti-deferral rule:** no listed hard task moves to a later phase unless this file records the move and the reason.

## v0.1.0 - Scaffold (DONE)
Compiles, CI green, structure correct, no domain logic.
- [x] Manifest, README, CHANGELOG, REPS, dual license, CI, deny, clippy, rustfmt, DIRECTIVES, ROADMAP.

## v0.2.0 - Foundation
- [ ] Image format (header, manifest, units, segments, debug maps), encoder/decoder, validation.
- [ ] Property tests: round trip, decoder never panics.

## v0.5.0 - Implementation
- [ ] Loading sequence: pager mapping, import binding, initialization order, loose-script loading, hot swap in dev mode.

## v0.9.0 - Hardening
- [ ] Fuzzing images; integrity tests; audit with the toolchain's publish mode as consumer.

## v1.0.0 - Stable
- [ ] Frozen after Mox publishes hybrid binaries through it (D18).
