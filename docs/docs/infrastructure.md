# Infrastructure Overview

## Infrastructure Assumptions

**Deployment Model:** Hybrid (cloud + limited on‑prem components)

The system supports multiple departments and requires reliability, scalability, and secure access.

## Key Components

### Compute

* Application servers for processing and business logic
* Analytics servers for reporting and KPI calculations

### Storage

* Centralized relational database for structured data
* Historical data store for trend analysis

### Network

* Secure internal network for on‑prem components
* Encrypted internet access for cloud services and remote users

## Justification

A hybrid infrastructure is appropriate because:

* Core data remains under organizational control
* Cloud resources handle variable analytical workloads
* Managers can securely access dashboards remotely

This balances control, cost, and flexibility.

## Scalability Considerations

* Horizontal scaling of processing servers
* Modular data pipelines for additional data sources
* Storage expansion without system redesign

The infrastructure supports gradual growth in data volume, users, and analytical complexity without structural changes.
