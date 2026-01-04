# Detections

Detection engineering framework for Sigma, YARA, Elastic/OpenSearch, and Splunk.

Focus: behavioral detections that survive tooling changes.

## Contents

- `sigma/`   – portable detections
- `yara/`    – file/memory heuristics
- `elastic/` – ES/OS queries and dashboards
- `splunk/`  – SPL detections
- `labs/`    – test cases + validation notes

## Principles

- Prefer behaviors over IOCs
- Document false positives + tuning
- Ship detections with reproducible test steps
