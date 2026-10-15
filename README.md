# WASTECONNECTIONS

> **Project:** `WASTECONNECTIONS` **Category:** WASTE_MANAGEMENT **Domain:** waste management **Upstream:** N/A **Upstream pin:** `N/A` **License:** Unknown **Verification:** 16/16 PASS **Date:** 2026-10-08

**Category:** WASTE_MANAGEMENT · **Ecosystem:** unknown · **Vendored upstream:** https://github.com/nicedoc/wasteconnections · **Pinned commit:** `see `.anticloud-provenance.json`` · **Vendor:** Anticloud FZ LLE

## What This Project Is

**Project:** `WASTECONNECTIONS` **Category:** WASTE_MANAGEMENT **Domain:** waste management **Upstream:** N/A **Upstream pin:** `N/A` **License:** Unknown **Verification:** 16/16 PASS **Date:** 2026-10-08

This is the upstream project, vendored at the pinned commit above and packaged offline-first. The 12 improvements Anticloud adds live in `anticloud/` and are described under *Anticloud Overlay* below. Every fact in this file traces to a file in this directory.

## Installation

```
# See the upstream README (linked above) for build steps.
```

## Usage

See the upstream README (linked above) for usage. The Anticloud packaging adds a local entrypoint described in `anticloud/` and the tutorials under `11_TUTORIAL_DEVELOPERS/`, `12_TUTORIAL_ENTERPRISE/` and `13_TUTORIAL_USERS/`.

## Anticloud Overlay

The 12 improvements live under `anticloud/`. Run the check suite from this directory:

```
python anticloud/bench/runner.py --cwd anticloud
```

## Benchmark Results

The suite is recorded in `BENCH.json`; no benchmark rows were found in this package.

## Licence

The upstream licence is preserved in `LICENSE` and `THIRD_PARTY_LICENSES/`. The Anticloud overlay is licensed under Anticommons 0.1.0 (`ANTICOMMONS_LICENSE.md`).

## Verification

SHA3-256 of `BENCH.json`:

```
c3732354c324b9cfd5cdc2bfbc4b3038ee7a3dda390bc702e147988cc4ee17bc
```

Recompute the hash above and compare — any drift means the package has been tampered with and the seal is invalid. This is a self-assessment; no external audit has been performed and a SOC 2 / NIST independent audit is committed post-funding.
