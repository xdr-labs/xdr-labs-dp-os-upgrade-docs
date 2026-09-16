# DP Offline Ubuntu Upgrade Documentation

Mintlify documentation for the current Stellar Cyber Data Processor offline Ubuntu OS upgrade and post-OS DP bringup workflow.

The site is driven from `docs.json` and is organized as an operator runbook:

1. Upgrade Work Plan
2. Ubuntu 24.04 Server Installation
3. Mirror Server Setup
4. DP Offline Ubuntu Upgrade
5. Post-Upgrade Validation

The active workflow covers:

- Ubuntu 16.04 → 18.04 → 20.04 → 22.04 → 24.04 sequential OS upgrades
- the current selective OS Core / Mirror Manager preparation workflow
- DP **6.6.0** Phase 2 bringup on Ubuntu 24.04
- AIO and DL/DA master/worker orchestration
- HTTP distribution from the Mirror Server to DP hosts
- validation, logs, retry, recovery, and troubleshooting

Older 6.5.0, `apt-cacher-ng`, and traditional full-mirror material is retained only as historical/reference context and must not be mixed into the active runbook.

This repository intentionally excludes private credentials, signing secrets, and environment-specific access information.
