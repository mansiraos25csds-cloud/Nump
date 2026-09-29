Open SwasthyaSetu (CARE-Link)

An offline-first, local-language care access and first-response platform for rural and underserved India.

Problem Statement

Accessibility and quality of public healthcare services in rural and underserved areas.

Rural healthcare faces a set of connected gaps:

Shortage of doctors at primary and community health facilities
Shortage of support staff such as nurses and technicians
Shortage of medical equipment at the point of care
Ambulances that only transport, with no initial medical service on the way
Poor connectivity in flood-prone, remote, and hilly regions, where digital tools often fail exactly when they are needed

Some states are already responding. For example, the Government of Maharashtra has piloted boat and bike ambulances for heavy monsoon and flood-prone regions. These reach patients that road ambulances cannot, but the pilots still need better first-response support and smarter dispatch.

Our Solution

Open SwasthyaSetu connects patients, ASHA workers, ambulance pilots, and health facilities through one system that keeps working with weak or no data connectivity.

It has two main parts:

Offline-first AI first-response copilot for boat and bike ambulance pilots, giving voice-driven, local-language guidance on the way to care.
CARE-Link, a care-matching layer that finds the right facility, not just the nearest one, and tracks the patient through to the outcome.
Key Features
First-Response Copilot
Voice-driven guidance in local languages
Offline decision support based on standard protocols
Data syncs automatically when signal returns
Emergency calling to 108/112, with fallback to calls or SMS when no data connection is available
Dynamic dispatch mode (road, bike, or boat) based on flood data
CARE-Link Care Matching
Multiple access modes: citizen, ASHA worker, and facility
Care Intent creation to capture what the patient actually needs
Emergency safety gate with 108/112 escalation for critical cases
Care Matching Engine that filters facilities by capability against IPHS standards
Data Freshness and Service Reliability engines so recommendations account for how current and trustworthy facility data is
ETTC (Effective Time-to-Care) and Care Readiness scoring
Best + Backup facility recommendation with explainability
Care-Ready Pass (QR or reference ID) for facility handoff and outcome tracking
Failure recovery through re-routing or eSanjeevani teleconsultation
Community Health Support
District-wise disease heatmap for spotting local health trends
Voice AI chatbot in local languages to guide ASHA workers on basic primary care, based on established protocols
1-week follow-up reminders so ASHA workers check on patients after care

The chatbot is designed as protocol-based decision support. It does not diagnose, and a trained health worker stays in control.

How It Works
Patient / ASHA request
        |
        v
  Care Intent created
        |
        v
  Emergency safety gate  ---- critical ---->  108/112 escalation
        |
        v
  Care Matching Engine (capability + freshness + reliability)
        |
        v
  Best + Backup facility recommendation (with explanation)
        |
        v
  Care-Ready Pass shared with facility
        |
        v
  Outcome tracking  ---- failure ---->  Re-route / eSanjeevani
        |
        v
  Follow-up reminder to ASHA (1 week)
Impact
Reduces time-to-care by matching patients to facilities that can actually treat them
Turns ambulances from transport into first-response care
Supports ASHA workers with local-language guidance and follow-up
Works in low-connectivity and flood-prone areas
Gives planners a district-level view of health trends
Tech Stack

Update this section with what you actually used.

Layer	Technology
Frontend / Mobile	e.g., React Native / Flutter
Backend	e.g., Node.js / FastAPI
Database	e.g., PostgreSQL / SQLite (offline sync)
AI / Voice	e.g., on-device speech recognition, rule-based protocol engine
Data sources	e.g., IPHS standards, facility data, ra<h>AVYAKTHA</h>
<p>Swasthya setu</p>
<h>AVYAKTHA</h>


