# System Architecture

## Overview

The Urban Intelligence Platform receives data from multiple external systems and vendors,
normalizes incoming information, stores standardized records, detects anomalies, and provides operational insights.

---

## High-Level Data Flow

External Systems
        │
        ▼
Raw Payload Ingestion
        │
        ▼
Validation Layer
        │
        ▼
Vendor Adapter
        │
        ▼
Normalization Layer
        │
        ▼
Canonical Data Model
        │
        ▼
SQLite Database
        │
 ┌──────┼─────────┐
 ▼      ▼         ▼
SQL   Anomaly   Dashboard
Analytics Detection
        │
        ▼
AI Knowledge Platform


---

## Main Components

### Raw Payload Ingestion

Receives data from sensors, APIs, and external systems.

---

### Validation Layer

Validates payload structure, required fields, schema version, and data quality.

---

### Vendor Adapter

Converts vendor-specific payloads into a common format.

---

### Normalization Layer

Converts field names, units, identifiers, and timestamps into the platform's canonical model.

---

### Canonical Data Model

Stores normalized data independently of the original vendor.

---

### Database

Stores:

- sensors
- assets
- events
- measurements
- anomalies
- vendor mappings

---

### SQL Analytics

Runs engineering and operational queries.

---

### Anomaly Detection Engine

Detects:

- data quality anomalies
- operational anomalies
- statistical anomalies

---

### Dashboard

Displays KPIs, alerts, and system health.

---

### AI Knowledge Platform

Allows engineers to ask technical questions based on documentation and historical data.
