# TMF013 - Signaling Data Transformation & Analytics API

## 📖 Overview
This repository contains the incubating OpenAPI 3.0 specification for **TMF013 Signaling Data Transformation & Analytics**. 
It bridges the gap between complex 3GPP telecommunications signaling protocols (S1-MME, S6a, N1) and high-value business operations by providing structured, actionable insights.

## 🚀 Core Capabilities
This API supports a Closed-Loop Operational Model through three primary mechanisms:
1. **Rule Management (`/analysisRule`)**: Configuration of detection thresholds and analysis rules.
2. **Reactive Analysis (`/analysisTask`)**: On-demand querying for device behaviors and network fault root-causes.
3. **Proactive Monitoring (`/sub`)**: Event-driven subscriptions for real-time risk pattern detection (e.g., SIM Swap, Geo-Anomaly).

## 💼 Business Use Cases (CMHK Implementation)
* **UC1**: Reactive behavior analysis (e.g., VIP Roaming Troubleshoot).
* **UC2**: Location consistency verification for Anti-Fraud.
* **UC3**: Device-SIM Binding & Machine-Card Anomaly Detection (IoT).

## 🛠️ API Visualization
To interact with the API definitions, click the link below to render the YAML in Swagger Editor:
👉 [View TMF013 in Swagger Editor](https://editor.swagger.io/?url=https://raw.githubusercontent.com/raymondho-cmhk/TMF013-Signaling-Data-Analytics/main/tmf013-openapi.yaml)
