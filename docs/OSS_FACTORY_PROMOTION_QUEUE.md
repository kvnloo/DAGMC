<!-- oss-factory:v1
{"id":"20261017-lane11-dagmc-fork-queue","kind":"state","project":"dagmc","from":"chatgpt","to":["factory","civ"],"status":"working","dedupe_key":"promotion-queue:svalinn/DAGMC","civ":{"city_id":"oss:dagmc"}}
-->

# Canonical Lane 11 upstream-promotion queue — svalinn/DAGMC

**Active repository-owned coordination document**, 2026-10-17. This fork has GitHub Issues disabled. Prior [legacy factory #143](https://github.com/kvnloo/oss-factory/issues/143) is preserved verbatim below, including authorship, URLs, and historical evidence; it is **not a second live queue**. [Factory #14](https://github.com/kvnloo/oss-factory/issues/14) is a directory only.

- Origin `svalinn/DAGMC` exact default-branch SHA: `3b46ba3c9708bd2bd3923dac79ef8ea601faad64`.
- Fork `kvnloo/DAGMC` exact default-branch SHA at fork creation: `3b46ba3c9708bd2bd3923dac79ef8ea601faad64`; this coordination branch is fork-only, never merged into a default branch by this worker.
- **Promotion contract:** existing live origin review and human authorization first; READY never grants publication; current project policies apply. Linear is retired. CI/CPU/source-only/synthetic/native H5M/transport evidence remain separate.
- **Verified new independent upstream-ready PRs this turn:** **none**. **Origin writes this turn:** **none**. **Native STEP→MOAB H5M→OpenMC:** **NOT RUN**; no reactor-performance or safety claim.

## Current live reconciliation (2026-10-17)

**No verified independent DAGMC source contribution is upstream-ready.** Native MOAB/DAGMC executable, H5M geometry and OpenMC transport unavailable in this execution environment; source or synthetic HDF5 checks are not a substitute. No new mock archive is being authored.

**Owners/provenance:** Svalinn DAGMC/MOAB project authors retain ownership; Bluemira and OpenMC integration work is referenced, not misattributed as DAGMC production work.

**Project rule:** origin contributions use `develop`, relevant tests/docs and a meaningful [CHANGELOG entry](https://github.com/svalinn/DAGMC/blob/develop/CONTRIBUTING.md). [Registry candidate #109](https://github.com/kvnloo/oss-factory/pull/109) remains unmerged, and currently routes coordination to the factory contrary to merged policy; correct within its existing owner review rather than minting a competing registration.

**Blocked gate:** no version-pinned native MOAB/PyMOAB H5M and `check_watertight` evidence. **Next merge-enabling task:** run real geometry material/surface-parent inspection plus independent negative control on actual H5M before selecting any DAGMC source defect.

## Historical record — verbatim source retained for audit, NOT current policy

Source: [factory issue #143](https://github.com/kvnloo/oss-factory/issues/143), captured before retirement. Its old Linear and factory-fallback language is **superseded** by [policy #130](https://github.com/kvnloo/oss-factory/pull/130) and the active header above.

<details>
<summary>Expand complete legacy queue body (unchanged)</summary>

<!-- oss-factory:v1
{"id":"20261016-lane11-dagmc-promotion-queue","kind":"state","project":"oss-factory","from":"chatgpt","to":["factory","civ"],"status":"working","dedupe_key":"promotion-queue:svalinn/DAGMC","civ":{"city_id":"oss:oss-factory"}}
-->

# DAGMC — upstream promotion queue
**Origin:** [svalinn/DAGMC](https://github.com/svalinn/DAGMC) · **fork:** [kvnloo/DAGMC](https://github.com/kvnloo/DAGMC) · **registry:** NOT on canonical `factory/projects.json` (registration needed before new tracked project work).

## How this queue works
This is the **one canonical, repo-specific promotion queue** for this repository's available work. Other issues, PRs, branches and wave archives remain the original source/evidence records—not competing promotion queues. [Factory-wide index #14](https://github.com/kvnloo/oss-factory/issues/14) links here. GitHub Issues are disabled on the fork; this issue therefore lives in the registered/temporary factory coordination repo.

**Promotion is not authorization.** A row enters **READY_FOR_HITL** only after (1) live requirement and owner/duplicate check, (2) exact-head native tests and required formatting/CI, (3) current maintainer review feedback reconciled, (4) narrow independent QA and a real fork commit, (5) project contribution policy, and (6) correct Linear origin-action state. Otherwise it remains CHECK, LIMITED, HOLD, IN_REVIEW, LANDED, or DISCARDED. Never promote old local tests as native H5M evidence. No origin comments/PRs/merges or worker lease are authorized by this queue. No default-branch merges.

Each update must link origin issue/PR, source branch/commit, actual test commands/result, contributor credit, unresolved blockers, and a single next action. Edit this queue rather than create a second one.

## Current disposition (2026-10-16)

| Work | State | Exact next prerequisite |
|---|---|---|
| Direct DAGMC fork contributions | **NONE CONFIRMED** | No open fork or factory-authored origin DAGMC PRs found; avoid fake promotion rows. |
| Bluemira/FastCTD generated H5M | **BLOCKED / INTEGRATION** | Produce real H5M using installed supported DAGMC/MOAB; inspect `CATEGORY`, `NAME=mat:...`, volume-to-material topology, shared surface parentage and native `check_watertight` output; compare against source STEP and OpenMC loading. |
| Local Waves 13–30 H5M/STEP checks | **LIMITED / CROSS-REPO** | Synthetic HDF5 checks and STEP geometry diagnostics are not native DAGMC or a DAGMC source patch. Evidence is held in the Bluemira queue, not counted as DAGMC upstream-ready. |
| Native DAGMC code defect | **NOT ESTABLISHED** | Determine whether any reproducer originates in DAGMC versus `cad_to_dagmc` export or Bluemira caller before modifying DAGMC source. |

**New upstream-ready DAGMC PRs: 0.** DAGMC CONTRIBUTING requires a test, `develop` base, applicable docs and a CHANGELOG entry for any future origin PR. Preserve BSD license/provenance. No origin write authorized.

**Credits:** Svalinn/DAGMC/MOAB authors and maintainers, Bluemira and OpenMC integrations, AI-assisted local QA.

</details>
