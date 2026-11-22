# Android AI Chat & Agent Library Research Template

> Duplicate this file for each candidate library. Fill unknown values as **Not verified** until independently tested.

## Metadata
- Library / repository:
- Current release / checked date:
- Maven coordinates / repository:
- SPDX license:
- Android minSdk / Kotlin / Gradle / Compose:
- Research owner:
- Device: Vivo X200 Ultra / Android 17
- Integration target: Vivo Offline Agent 0.2.0

## Evidence (link each claim to a primary source)
| Claim | Source link | Verified in docs? | Reproduced on device? |
|---|---|---|---|
| Core features | | | |
| Android supported | | | |
| Offline inference | | | |
| Streaming | | | |
| Tool calling | | | |
| Security controls | | | |

## Build compatibility
- Gradle settings:
- Dependency tree:
- AAR/APK growth:
- minSdk and Java desugaring:
- Kotlin and Compose version compatibility:
- Repro command:

## Local-first tests
- [ ] localhost only / no cloud endpoint
- [ ] Termux llama.cpp GGUF inference through /v1/chat/completions
- [ ] Persian RTL and UTF-8
- [ ] Streaming / cancel / resume
- [ ] Offline mode after airplane toggle
- [ ] 30 minute thermal, RAM and battery measurements
- [ ] App restart, server kill, reconnect

## Agent security tests
- [ ] No model-generated command executed without approval
- [ ] Allowlisted paths and tools
- [ ] Injection tests via retrieved file content
- [ ] User denial honored
- [ ] Shizuku/ADB optional; no privilege escalation
- [ ] Timeouts and audit logs

## Benchmark table
| Metric | Baseline | Candidate | Notes |
|---|---|---|---|
| APK size | | | |
| Idle RAM | | | |
| First token latency | | | |
| Decode tokens/sec | | | |
| Battery drain | | | |
| Crash/reconnect | | | |

## Go / No-go decision
- Decision:
- Advantages:
- Risks:
- Unverified assumptions:
- Rollback plan:
- Next issue / pull request:
