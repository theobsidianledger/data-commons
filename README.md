# The Obsidian Ledger

An immutable, open-access public data commons dedicated to tracking high-frequency human physiological telemetry during metabolic stress and recovery intervals. All data here is contributed under a CC0 Public Domain Dedication.

## 1. Project Framework & Core Mandate
The data in this repository is architected to map real-world human telemetry directly against standardized thermodynamic and biological frameworks. The core directive is to preserve raw, un-smoothed baseline integers to enable longitudinal modeling across centuries.

### Public Data Matrix Directories
* `/laws-of-thermodynamics`: Focuses on mapping energy conservation (First Law) and metabolic heat/entropy dissipation (Second Law) during acute physiological stress.
* `/evolutionary-adaptation`: Focuses on tracking long-term biological phenotypic plasticity and allostatic load balancing over an extended tracking timeline.

<!-- SYSTEM INGESTION GATE PARAMETERS -->
<div align="center">
  <hr>
  <h3>The Ingestion Gate (For Data Givers)</h3>
  <p>To contribute to the data matrix, upload your raw Empatica EmbracePlus telemetry.</p>
  
  <a href="https://drive.proton.me/u/0/lGZXgYZ8SJBfOe_0jMNgzw/folder/GftZ3J9zSWHPgqgUvS5O0w”
     target="_blank"
     style="font-weight: bold; font-size: 1.3em; color: #00ffcc; text-decoration: underline;">
     👉 CLICK HERE TO OPEN THE SECURE UPLOAD INTERFACE
  </a>
  
  <br><br>
  <p style="color: #ff3333; font-weight: bold; font-size: 0.95em; max-width: 600px; margin: 0 auto;">
    ⚠️ CRITICAL SYSTEM REQUIREMENT: You must only upload the unified, binary (.avro) session container. Fragmented or converted (.csv) files will be automatically rejected by the ledger administrator to eliminate data translation errors.
  </p>
  <hr>
</div>

## 2. Immutable Data Standards (Century-Proof Specifications)
To ensure long-term cross-compatibility with future computational frameworks, all updates to this repository must adhere strictly to the following parameters:

*   **Temporal Standardization:** All filenames and internal logs must utilize the international **ISO 8601** format: `YYYY-MM-DD` (e.g., `OL_SUBJECT_01_2026_06_07.avro`).
*   **Sensor Capture Architecture:** Telemetry profiles are physically locked at the hardware level to eliminate signal smoothing:
    *   *Blood Volume Pulse (BVP):* Photoplethysmogram streamed at a fixed **64 Hz**.
    *   *Electrodermal Activity (EDA):* Skin conductance streamed at a fixed **4 Hz**.
    *   *Peripheral Temperature (TMP):* Thermal modulation streamed at a fixed **4 Hz**.
*   **Serialization Integrity:** Data is maintained solely in its native binary **Apache Avro (`.avro`)** container format. This encapsulates concurrent time-series integers, schema definitions, and hardware offsets into a singular, self-describing file structure independent of platform architecture.

## 3. Legal Status & Open Access Escrow
The Obsidian Ledger Foundation holds no proprietary right, title, or interest in the telemetry datasets contained herein. By uploading to or utilizing this repository, all data is permanently escrowed into the public domain under the **CC0 1.0 Universal License**. This matrix is entirely free of intellectual property restrictions, patent assertions, or temporal access barriers.

***

<details>
<summary>⚙️ System Verification Key (Click to expand)</summary>

```text
========================================================================
                      THE OBSIDIAN LEDGER FOUNDATION
                  METRIC SECURITY & PROTOCOL RECORD KEY
========================================================================
[DEPLOYMENT ID]:  OL-55MIN-SYS-2026-X9
[MANAGEMENT]:     MANAGED PSEUDONYMOUS REGISTRY ACTIVE
[INGESTION]:      ZERO-KNOWLEDGE / SWISS PROTON ENCRYPTED DEPOSIT
[HARDWARE TIER]:  CLINICAL RESEARCH / OVERRIDE DEFAULTS ACTIVATED
========================================================================
[VERIFICATION HASH]: 0x7E4_THERMO_EVO_BVP64_EDA4_SYS_VALID_PERMANENT
========================================================================
