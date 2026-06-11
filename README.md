# Smart Waste Management System (Phase 1)

♻️ **Course:** System Requirements Specification (SRS)  
🏢 **Institution:** Faculty of Computing & AI (FCAI)  
👥 **Group:** 3 (100 Points Evaluation)

---

## 🏢 Overview
The **Smart Waste Management System** is an enterprise-grade urban infrastructure solution engineered to preserve city cleanliness, optimize municipal asset distribution, and improve operational efficiency in waste collection. By implementing automated fill-level notifications, dynamic route optimization, and transparent public grievance modules, the platform mitigates the hazards of overflowing trash bins and ensures streamlined municipal workflows.

---

## ⚙️ Core System Modules & Scope
The system architecture spans multiple key operational components:
* **Citizen Portal:** Allows public users to report overflowing bins, submit neighborhood clean-up complaints, and pin exact geolocation coordinates.
* **Driver Dashboard:** Provides automated route optimization scripts, matches driver schedules to active bin locations, and logs collection confirmation alerts.
* **Supervisor Control Center:** Tracks active personnel, assigns reported municipal complaints to field technicians, and monitors regional collection milestones.
* **Technician Operations:** Receives automated work order dispatch notifications and logs maintenance/resolution updates for damaged assets.
* **Admin Module:** Complete database control over application user profiles, hardware node registrations (IoT simulation profiles), and general system telemetry.

---

## 📊 Requirements & Abbreviation Index
### Functional Requirements (FR) Preview
The system satisfies structural multi-tier user pathways with an explicit **Acceptance Test (AT)** paired with each specification:
1. **FR1 (Citizen Auth):** Register and log in securely.
2. **FR2 (Complaint Submission):** Log location-based waste complaints.
3. **FR3 (Live Monitoring):** Display color-coded active fill-state indicators.
4. **FR4 (Driver Route Execution):** Generate dynamic shortest-path calculations.
5. **FR5 (Task Verification):** Drivers explicitly report empty states on clearing tasks.
6. **FR6 (Supervisor Dispatch):** Manual and automated triage of localized technician complaints.

### Non-Functional Requirements (NFR) Targets
* **Performance:** Maximum routing algorithm computational execution delay under 3 seconds.
* **Availability:** 99.9% application uptime targeting structural cloud servers.
* **Scalability:** System capabilities map gracefully up to 10,000 parallel active endpoint requests.
* **Security:** Complete password masking via industry-standard cryptography layers.

---

## 🛠️ Phase 1 Deliverables
The repository hosts the complete structural foundational assets required under Phase 1 requirements:
* **`Purpose & Scope Statements`** $\rightarrow$ High-level strategic vision framing the platform's urban impact.
* **`User & Stakeholder Matrices`** $\rightarrow$ Formal breakdown profiling Citizens, Drivers, Supervisors, Technicians, and Admins.
* **`Comprehensive Use Case Diagram`** $\rightarrow$ Architectural actor boundary map pinning 16 clear system actions.
* **`Use Case Specification Tables`** $\rightarrow$ Granular data tracking preconditions, nominal paths, and postconditions.
* **`System Acceptance Test (AT) Plan`** $\rightarrow$ Complete QA maps linking input assertions to explicit expected criteria.

---

## 📂 Project Structure
```text
├── Docs/
│   └── System_Requirements_Specification_Phase_1.docx  # Full formal SRS artifact
├── Diagrams/
│   └── Use_Case_Diagram.png                           # Actor-system boundary map
└── README.md                                          # Project directory navigation
📌 Assumptions & Engineering Constraints
Constant Network Connectivity: Assumes active edge nodes (simulated bins) and client handsets maintain valid internet handshakes over cellular or municipal grids.

Precise Geolocation Data: Assumes standard target device GPS modules return accurate horizontal coordinate values for path routing.

Concrete Technical Limits: Designed exclusively around the logical software constraints of the Phase 1 specification framework.

👥 Team Members & Authors (Group 3)
Mena Mohamed Sultan (ID: 20245068) 

Gehan Mohamed Selim (ID: 20245016) 

Sophia Muhammad Raafat (ID: 20247002) 

Youssef Mahmoud elSawy (ID: 20246137) 
