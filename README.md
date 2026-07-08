# ICSR-  icsr-case-processing/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── docs/
│   ├── Business_Requirements.md
│   ├── Workflow_Diagram.md
│   ├── SOP_Reference.md
│   └── User_Guide.md
│
├── src/
│   ├── frontend/
│   │   ├── dashboard/
│   │   ├── case-entry/
│   │   ├── search/
│   │   └── reports/
│   │
│   ├── backend/
│   │   ├── api/
│   │   ├── services/
│   │   ├── database/
│   │   └── validation/
│   │
│   └── common/
│
├── database/
│   ├── schema.sql
│   └── seed-data.sql
│
├── test/
│   ├── unit/
│   ├── integration/
│   └── performance/
│
└── deployment/
    ├── docker/
    └── kubernetes/    
    Case Receipt
      │
      ▼
Case Registration
      │
      ▼
Triage
      │
      ▼
Data Entry
      │
      ▼
Medical Coding
(MedDRA/WHO Drug)
      │
      ▼
Quality Review
      │
      ▼
Medical Review
      │
      ▼
Regulatory Reporting
      │
      ▼
Case Closure
# ICSR Case Processing System

A Pharmacovigilance workflow application for managing Individual Case Safety Reports (ICSRs).

## Features
- Case Intake
- Triage
- Data Entry
- MedDRA Coding
- Quality Review
- Medical Review
- Regulatory Reporting
- Audit Trail
- KPI Dashboard

## Tech Stack
- Frontend: React
- Backend: Node.js / Python
- Database: PostgreSQL
- Authentication: Azure AD
- Hosting: Azure

## Users
- Case Processor
- Medical Coder
- Quality Reviewer
- Drug Safety Physician
- Administrator
