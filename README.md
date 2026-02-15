# 🏥 SignAI: Agentic ISL Triage for Emergency Care

> **Breaking the silence in Indian Emergency Rooms.** > SignAI uses Multimodal Agentic AI to bridge the 6.32s gap between a deaf patient's gestures and life-saving medical action.

---

## 🚀 The "Bharat" Impact
- **Problem:** 18M+ Indians use ISL, yet 99% of ERs have no translators, leading to fatal triage delays.
- **Solution:** A kiosk-based agent that interprets **Indian Sign Language (ISL)**, assesses trauma, and triggers hospital alerts in **<7 seconds**.
- **Compliance:** 100% **DPDP Act 2023** compliant (Data stays in Mumbai `ap-south-1`).

---

## 🧠 The Tech Stack (AWS-Native)
- **Model:** `Amazon Nova Pro` (Multimodal Vision for ISL & Facial Distress).
- **Orchestration:** `Amazon Bedrock Agents` (Autonomous medical reasoning & triage).
- **Safety:** `Bedrock Guardrails` (Real-time PII masking & medical safety filters).
- **Compute:** `AWS Lambda` (Serverless/Zero-idle cost).
- **Data:** `AWS HealthLake` (FHIR-standardized health records).

---

## ⚡ Mechanism in Action
| Step | Action | Service |
| :--- | :--- | :--- |
| **1. Capture** | WebRTC Video Stream from Kiosk | Amazon S3 |
| **2. Interpret** | 89% Confidence Recognition of "Head Trauma" | Amazon Nova Pro |
| **3. Triage** | Severity Assessment & FHIR Log | Bedrock Agents |
| **4. Alert** | Multilingual SMS/WhatsApp to Dr. on Duty | Amazon SNS |

> **Latency Benchmark:** 6.32s from Sign to Alert.

---

## 📊 Economics of Scale
- **OpEx:** ~₹4.50 ($0.06) per patient session.
- **CapEx:** ₹1.8L per ruggedized kiosk unit.
- **Sustainability:** 100% Serverless architecture = **Zero cost when idle**.

---

## 🛠️ Setup & Installation

1. **Clone the Repo:**
   ```bash
   git clone [https://github.com/](https://github.com/)varshasampath04-maker/SignAI.git
   cd SignAI
