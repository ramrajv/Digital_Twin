# PROJECT GANTT SCHEDULE & RESOURCE ALLOCATION
## Hybrid Digital Twin for Aero Gas Turbine Engine Health Usage Monitoring System
### 36-Month Timeline with Weekly Detail (First 8 Weeks) and Monthly Thereafter

---

## SECTION 1: PROJECT OVERVIEW & KEY DATES

| Parameter | Value |
|-----------|-------|
| **Project Start Date** | Month 0, Week 1 (Day 1) |
| **Project End Date** | Month 36, Week 156 (Day 1,092) |
| **Total Project Duration** | 36 months (156 weeks, 1,092 days) |
| **Number of Phases** | 5 milestones (MS-1 to MS-5) |
| **Reporting Cadence** | Weekly (Weeks 1-8), Monthly (Weeks 9-156) |
| **Review Gates** | PDR (W26), CDR (W52), SIR (W78), ATP (W130), Completion (W156) |

---

## SECTION 2: MILESTONE SCHEDULE & PAYMENT GATES

| Milestone | Phase | Start (Week) | End (Week) | Duration | Target Delivery | Payment Gate | Cumulative % |
|-----------|-------|--------------|-----------|----------|-----------------|--------------|-------------|
| **MS-1** | PDR | 1 | 26 | 6 months | SRD, PDD approved, tech survey complete | 20% (₹3.00 Cr) | 20% |
| **MS-2** | Detailed Design | 27 | 52 | 6 months | SDD, DDD approved, design review complete | 20% (₹3.00 Cr) | 40% |
| **MS-3** | Prototype & CDR | 53 | 78 | 6 months | CDD approved, prototype code, V&V reports | 20% (₹3.00 Cr) | 60% |
| **MS-4** | Production & ATP | 79 | 130 | 12 months | ATP executed, acceptance reports, user manual | 20% (₹3.00 Cr) | 80% |
| **MS-5** | Completion & ToT | 131 | 156 | 6 months | Full documentation, ToT executed, IPR shared | 20% (₹3.00 Cr) | 100% |

---

## SECTION 3: DETAILED WORK BREAKDOWN STRUCTURE (WBS) - MS-1 (WEEKS 1-26)

### Phase: Preliminary Design Review (PDR) - 0 to 6 Months

| WBS ID | Task Name | Start Week | End Week | Duration (Weeks) | Start Month | End Month | Lead Role | Supporting Roles | Effort (PM) | Dependency |
|--------|-----------|-----------|---------|------------------|-------------|----------|-----------|------------------|------------|-----------|
| **1.1** | Project Initiation & Governance | 1 | 4 | 4 | M0 | M0.5 | Project Manager | Program Coordinator | 2 | - |
| **1.2** | Requirement Elicitation & Clarification | 5 | 10 | 6 | M1.2 | M2.4 | Systems Engineer | PM, DRDO Liaison | 4 | 1.1 |
| **1.3** | System Requirements Document (SRD) | 11 | 18 | 8 | M2.6 | M4.3 | Systems Engineer | PM, QA Lead | 5 | 1.2 |
| **1.4** | Technology Survey & Critical Tech Identification | 6 | 17 | 12 | M1.4 | M4.1 | Lead ML/AI Scientist | Lead Thermo Eng, Academics | 8 | 1.1 |
| **1.5** | High-Level DT Framework & Architecture | 15 | 22 | 8 | M3.6 | M5.3 | Software Architect | Systems Eng, Lead Roles | 6 | 1.4 |
| **1.6** | PDD Finalization & PDR Approval | 19 | 26 | 8 | M4.6 | M6.3 | Project Manager | Systems Eng, All Leads | 4 | 1.3, 1.5 |

**MS-1 Summary:** 26 weeks, 29 person-months effort, 6 core tasks, 50+ review meetings with DRDO.

---

## SECTION 4: DETAILED WBS - MS-2 (WEEKS 27-52)

### Phase: Detailed Design & Engineering Prototype Definition - 6 to 12 Months

| WBS ID | Task Name | Start Week | End Week | Duration (Weeks) | Start Month | End Month | Lead Role | Supporting Roles | Effort (PM) | Dependency |
|--------|-----------|-----------|---------|------------------|-------------|----------|-----------|------------------|------------|-----------|
| **2.1** | Feasibility & Modeling Strategy per Component | 27 | 32 | 6 | M6.0 | M7.7 | Lead Thermo Eng | Lead ML Sci, Systems Eng | 8 | 1.6 |
| **2.2** | Detailed Design of 17 DT Blocks | 33 | 48 | 16 | M7.9 | M11.5 | Lead Thermo Eng | Lead ML Sci, Data Eng | 20 | 2.1 |
| **2.3** | Data Strategy & Pre-processing Design | 27 | 38 | 12 | M6.0 | M9.1 | Data Engineer | Lead ML Sci, QA Lead | 10 | 1.6 |
| **2.4** | Integrated System Design (17 DT Blocks) | 39 | 48 | 10 | M9.3 | M11.5 | Software Architect | Systems Eng, Lead Thermo | 12 | 2.2 |
| **2.5** | Hardware & Platform Definition | 35 | 42 | 8 | M8.3 | M10.0 | Systems Engineer | Software Arch, QA Lead | 6 | 2.1 |
| **2.6** | SDD/DDD Finalization & Design Review | 45 | 52 | 8 | M10.7 | M12.4 | Systems Engineer | PM, All Technical Leads | 6 | 2.2, 2.4, 2.5 |

**MS-2 Summary:** 26 weeks, 62 person-months effort, 6 major tasks, BOM finalized, detailed designs frozen.

---

## SECTION 5: DETAILED WBS - MS-3 (WEEKS 53-78)

### Phase: Prototype Development & Critical Design Review - 12 to 18 Months

| WBS ID | Task Name | Start Week | End Week | Duration (Weeks) | Start Month | End Month | Lead Role | Supporting Roles | Effort (PM) | Dependency |
|--------|-----------|-----------|---------|------------------|-------------|----------|-----------|------------------|------------|-----------|
| **3.1** | Prototype Implementation of DT Blocks | 53 | 66 | 14 | M12.5 | M15.7 | Lead Thermo Eng | Lead ML Sci, Soft Arch, JE | 24 | 2.6 |
| **3.2** | Data Handling, Training & Validation | 53 | 68 | 16 | M12.5 | M16.2 | Data Engineer | Lead ML Sci, Lead Thermo | 18 | 2.3 |
| **3.3** | Integrated DT Prototype Assembly | 63 | 72 | 10 | M15.0 | M17.1 | Software Architect | Lead Thermo Eng, Soft Eng | 14 | 3.1 |
| **3.4** | Performance Regime Clustering & Tuning | 65 | 72 | 8 | M15.5 | M17.1 | Lead ML/AI Scientist | Data Engineer, Lead Thermo | 10 | 3.2 |
| **3.5** | Prototype Testing & Validation (Offline/Online) | 67 | 76 | 10 | M16.0 | M18.0 | QA Lead | Lead Thermo Eng, QA Team | 12 | 3.3, 3.4 |
| **3.6** | QA & Process Documentation | 70 | 75 | 6 | M16.7 | M17.9 | QA Lead | PM, Technical Writers | 8 | 3.5 |
| **3.7** | CDD & Critical Design Review (CDR) | 73 | 78 | 6 | M17.4 | M18.5 | Systems Engineer | PM, All Leads | 6 | 3.6 |

**MS-3 Summary:** 26 weeks, 92 person-months effort, 7 major implementation tasks, prototype integrated and validated.

---

## SECTION 6: DETAILED WBS - MS-4 (WEEKS 79-130)

### Phase: Production & Supply, ATP Execution - 18 to 30 Months

| WBS ID | Task Name | Start Week | End Week | Duration (Weeks) | Start Month | End Month | Lead Role | Supporting Roles | Effort (PM) | Dependency |
|--------|-----------|-----------|---------|------------------|-------------|----------|-----------|------------------|------------|-----------|
| **4.1** | Hardware Procurement & Setup | 79 | 90 | 12 | M18.5 | M21.2 | Systems Engineer | Soft Arch, Admin, Vendors | 8 | 3.7 |
| **4.2** | Production Software Hardening | 85 | 100 | 16 | M20.2 | M23.7 | Software Architect | GUI Dev, Soft Eng, QA | 18 | 3.7 |
| **4.3** | Hardware & Software Integration | 99 | 110 | 12 | M23.5 | M26.1 | Software Architect | Systems Eng, Soft Team | 14 | 4.1, 4.2 |
| **4.4** | ATP Procedure & Execution | 109 | 124 | 16 | M26.0 | M29.4 | QA Lead | PM, All Teams, DRDO | 16 | 4.3 |
| **4.5** | On-Site Model Training & Validation | 95 | 114 | 20 | M22.6 | M27.1 | Lead ML/AI Scientist | Data Eng, Lead Thermo, JE | 22 | 4.2 |
| **4.6** | Acceptance Reports & Final Sign-off | 125 | 130 | 6 | M29.6 | M30.8 | QA Lead | PM, Systems Eng | 4 | 4.4, 4.5 |

**MS-4 Summary:** 52 weeks, 82 person-months effort, 6 production/validation tasks, on-site DRDO deployment and ATP.

---

## SECTION 7: DETAILED WBS - MS-5 (WEEKS 131-156)

### Phase: Documentation, ToT & Project Closure - 30 to 36 Months

| WBS ID | Task Name | Start Week | End Week | Duration (Weeks) | Start Month | End Month | Lead Role | Supporting Roles | Effort (PM) | Dependency |
|--------|-----------|-----------|---------|------------------|-------------|----------|-----------|------------------|------------|-----------|
| **5.1** | Final Documentation Set | 131 | 142 | 12 | M31.0 | M33.5 | Project Manager | Tech Writers, All Leads | 8 | 4.6 |
| **5.2** | Production & Delivery of Final Units | 131 | 140 | 10 | M31.0 | M33.1 | Software Architect | Systems Eng, QA, Admin | 10 | 4.6 |
| **5.3** | Transfer of Technology (ToT) | 141 | 150 | 10 | M33.3 | M35.5 | Lead Thermo Eng | Lead ML Sci, All Leads | 12 | 5.1 |
| **5.4** | IPR Sharing & Legal Closure | 145 | 150 | 6 | M34.4 | M35.5 | Project Manager | Legal Advisor | 3 | 5.1 |
| **5.5** | Project Success & Completion Reports | 150 | 156 | 7 | M35.5 | M37.0 | Project Manager | Systems Eng, QA Lead | 5 | 5.3, 5.4 |

**MS-5 Summary:** 26 weeks, 38 person-months effort, 5 closure tasks, full knowledge transfer to DRDO.

---

## SECTION 8: RESOURCE ALLOCATION & TEAM COMPOSITION

### 8.1 Core Project Team Roles (Full-Time & Part-Time)

| Role | Count | FTE | Monthly Rate (INR) | Annual Cost (INR) | 36-Month Cost (INR) | Project Span |
|------|-------|-----|-------------------|------------------|-------------------|------------|
| **Project Manager** | 1 | 1.0 | ₹3,50,000 | ₹42,00,000 | ₹1,26,00,000 | 36 months (full-time) |
| **Lead Thermodynamics Engineer** | 1 | 1.0 | ₹4,00,000 | ₹48,00,000 | ₹1,44,00,000 | 36 months (full-time) |
| **Lead ML/AI Scientist** | 1 | 1.0 | ₹4,50,000 | ₹54,00,000 | ₹1,62,00,000 | 36 months (full-time) |
| **Software Architect** | 1 | 0.8 | ₹3,50,000 | ₹33,60,000 | ₹1,00,80,000 | 30 months (80% after M24) |
| **Data Engineer** | 1 | 1.0 | ₹3,00,000 | ₹36,00,000 | ₹1,08,00,000 | 36 months (full-time) |
| **GUI/UX Developer** | 1 | 0.6 | ₹2,50,000 | ₹15,00,000 | ₹45,00,000 | 18 months (from M12 onwards) |
| **Quality Assurance Lead** | 1 | 1.0 | ₹2,80,000 | ₹33,60,000 | ₹1,00,80,000 | 36 months (full-time) |
| **Systems Engineer** | 1 | 0.5 | ₹2,80,000 | ₹16,80,000 | ₹50,40,000 | 12 months (part-time M0-M12) |
| **Junior Thermodynamics Engineer** | 2 | 1.0 | ₹1,50,000 | ₹36,00,000 | ₹1,08,00,000 | 24 months (M6-M30) |
| **ML Engineer / Research Associate** | 2 | 1.0 | ₹1,80,000 | ₹43,20,000 | ₹1,29,60,000 | 30 months (M0-M30) |
| **Software Engineer / Developer** | 3 | 1.0 | ₹1,80,000 | ₹64,80,000 | ₹1,94,40,000 | 24 months (M12-M36) |
| **Data Scientist / Analyst** | 1 | 1.0 | ₹2,00,000 | ₹24,00,000 | ₹72,00,000 | 18 months (M6-M24) |
| **QA Engineer / Test Specialist** | 2 | 0.8 | ₹1,20,000 | ₹23,04,000 | ₹69,12,000 | 12 months (M18-M30) |
| **Technical Writer** | 2 | 0.4 | ₹1,00,000 | ₹9,60,000 | ₹28,80,000 | 12 months (M24-M36) |
| **Program Coordinator** | 1 | 0.5 | ₹80,000 | ₹4,80,000 | ₹14,40,000 | 36 months (part-time) |
| **TOTAL TEAM** | **20** | **14.0 avg** | - | **~₹5,80,00,000** | **~₹4.50 Cr (36M aggregate)** | - |

**Average Project Team Size:**
- Months 0-6 (MS-1): 8 FTE
- Months 6-12 (MS-2): 12 FTE  
- Months 12-18 (MS-3): 16 FTE (peak)
- Months 18-30 (MS-4): 14 FTE
- Months 30-36 (MS-5): 10 FTE

---

## SECTION 9: ROLE-WISE TASK ALLOCATION (WHO DOES WHAT)

### 9.1 Project Manager Responsibilities

| Milestone | Primary Tasks | % Effort | Key Deliverables |
|-----------|---------------|----------|------------------|
| **MS-1** | Governance setup, requirement coordination, PDR prep | 30% | Project charter, RACI, SRD approval |
| **MS-2** | Design review coordination, schedule tracking | 25% | Design review minutes, approval memos |
| **MS-3** | CDR preparation, risk monitoring, status reports | 25% | CDR pack, monthly reports, risk register |
| **MS-4** | ATP coordination, hardware delivery tracking, on-site liaison | 35% | ATP reports, acceptance documentation |
| **MS-5** | Documentation oversight, ToT coordination, project closeout | 40% | Final docs, completion report, lessons learned |

### 9.2 Lead Thermodynamics Engineer Responsibilities

| Milestone | Primary Tasks | % Effort | Key Deliverables |
|-----------|---------------|----------|------------------|
| **MS-1** | Tech survey, DT architecture preliminary design | 40% | Tech survey report, architecture sketches |
| **MS-2** | Detailed design of 9 core component models | 80% | DDD with thermodynamic equations, maps |
| **MS-3** | Model implementation, validation design | 80% | Source code for physics models, V&V plan |
| **MS-4** | On-site training, model tuning with DRDO data | 75% | Trained models, tuning reports |
| **MS-5** | ToT training delivery, documentation review | 50% | Training materials, handover package |

### 9.3 Lead ML/AI Scientist Responsibilities

| Milestone | Primary Tasks | % Effort | Key Deliverables |
|-----------|---------------|----------|------------------|
| **MS-1** | AI/ML tech survey, critical tech identification | 35% | Tech survey section, ML roadmap |
| **MS-2** | Data strategy, ML model architecture design | 75% | DDD with ML models, feature design |
| **MS-3** | ML model implementation, training, tuning | 85% | Trained ML models, performance reports |
| **MS-4** | On-site model validation, anomaly detection tuning | 80% | Validation reports, anomaly algorithms |
| **MS-5** | ToT on ML methods, documentation | 60% | Training slides, algorithm documentation |

### 9.4 Software Architect Responsibilities

| Milestone | Primary Tasks | % Effort | Key Deliverables |
|-----------|---------------|----------|------------------|
| **MS-1** | Integration architecture, tool evaluation | 25% | Architecture diagrams, tool recommendations |
| **MS-2** | System design for 17 DT blocks, integration plan | 70% | SDD, integration specification |
| **MS-3** | Prototype assembly, integration testing | 80% | Integrated prototype code, test logs |
| **MS-4** | Production hardening, real-time optimization | 85% | Production-grade software, performance reports |
| **MS-5** | Final software delivery, version control setup | 60% | Source code handover, build documentation |

### 9.5 Data Engineer Responsibilities

| Milestone | Primary Tasks | % Effort | Key Deliverables |
|-----------|---------------|----------|------------------|
| **MS-1** | Data requirements definition | 15% | Data handling plan outline |
| **MS-2** | Data pre-processing pipeline design | 65% | Data schemas, ETL specifications |
| **MS-3** | Data pipeline implementation, feature extraction | 85% | Automated pipelines, feature repositories |
| **MS-4** | On-site data handling, model training support | 90% | Trained datasets, calibration data |
| **MS-5** | Data handover documentation | 30% | Data management procedures |

### 9.6 QA Lead Responsibilities

| Milestone | Primary Tasks | % Effort | Key Deliverables |
|-----------|---------------|----------|------------------|
| **MS-1** | QA plan, test strategy development | 20% | QA plan, test framework outline |
| **MS-2** | Test case design, acceptance criteria | 35% | 500+ test cases, ATP outline |
| **MS-3** | Prototype testing, defect tracking | 70% | Test reports, defect logs, V&V report |
| **MS-4** | ATP execution, acceptance testing | 85% | ATP execution reports, acceptance sign-off |
| **MS-5** | Final test closure, lessons learned | 25% | Final test summary, QA closure report |

---

## SECTION 10: WEEKLY DETAIL (MS-1, FIRST 8 WEEKS)

### Critical Path for MS-1 PDR Phase

| Week | Task ID | Task Name | Activity | Lead Role | Concurrent Tasks | Deliverables Due |
|------|---------|-----------|----------|-----------|------------------|-----------------|
| **W1** | 1.1 | Project Initiation | Kickoff meeting, charter, org chart | PM | 1.1 | Project charter signed |
| **W2** | 1.1 | Project Initiation | RACI setup, governance, tooling | PM | 1.2 start | Governance docs |
| **W3** | 1.1, 1.4 | Init + Tech Survey | Stakeholder interviews, initial planning | PM, Lead ML/Thermo | 1.2, 1.4 | Kick-off complete |
| **W4** | 1.1 | Project Initiation | Final team onboarding, process setup | PM | 1.2, 1.4 | Toolchain ready |
| **W5** | 1.2, 1.4 | Requirements + Tech Survey | Requirements workshop, tech search | Sys Eng, Lead ML/Thermo | 1.3, 1.5 | Requirements draft, tech list |
| **W6** | 1.2, 1.4 | Requirements + Tech Survey | Requirements refinement, literature review | Sys Eng, Academics | 1.3, 1.4 | Requirements refined, survey ongoing |
| **W7** | 1.2, 1.4 | Requirements + Tech Survey | Mutual req finalization, tech analysis | All leads | 1.3 | Draft requirements document |
| **W8** | 1.3, 1.4 | SRD + Tech Survey | SRD drafting, tech survey completion | Sys Eng, Lead ML/Thermo | 1.5, 1.4 | SRD v0.5, tech survey draft |

---
## SECTION 11: UPDATED FINANCIAL SUMMARY
| **Category** | **Cost (₹ Cr)** | **% Total** |
|--------------|-----------------|-------------|
| **Manpower** | **4.50** | 29% |
| **Hardware** | 2.04 | 13% |
| **Software** | 0.98 | 6% |
| **Infrastructure** | 0.43 | 3% |
| **Contingency** | 0.41 | 3% |
| **Testing/Travel** | 1.50 | 10% |
| **Academic** | 0.57 | 4% |
| **Overhead (10%)** | 1.41 | 9% |
| **Other** | 3.46 | 23% |
| **TOTAL** | **₹15.30 Cr** | **100%** |
---

## SECTION 12: CRITICAL PATH ANALYSIS

### Critical Path (Longest Sequence of Dependent Tasks)

**Path 1 (26 weeks, MS-1):**
1.1 → 1.2 → 1.3 → 1.5 → 1.6 (PDR approval)

**Path 2 (52 weeks, MS-1+MS-2):**
1.1 → 1.4 → 1.5 → 2.2 → 2.4 → 2.6 (SDD/DDD approval)

**Path 3 (78 weeks, MS-1+MS-2+MS-3):**
1.6 → 2.2 → 3.1 → 3.3 → 3.5 → 3.7 (CDD approval)

**Path 4 (130 weeks, MS-1+MS-2+MS-3+MS-4):**
3.7 → 4.1 → 4.3 → 4.4 → 4.6 (ATP completion)

**Critical Slack Tasks (High Risk):**
- Task 1.3 (SRD): 2-week buffer only
- Task 2.2 (DT block design): 4-week buffer
- Task 3.1 (Prototype implementation): 2-week buffer
- Task 4.4 (ATP execution): 6-week buffer (high variability with DRDO)

---

## SECTION 13: RESOURCE LOADING BY PHASE

### Person-Month Effort Distribution

```
Total Project Effort: ~305 Person-Months (36-month duration, ~14 FTE average)

MS-1 (Weeks 1-26): 29 PM
├─ Project Manager: 3 PM
├─ Systems Engineer: 4 PM
├─ Lead Thermo Eng: 5 PM
├─ Lead ML/AI Sci: 7 PM
└─ Supporting: 10 PM

MS-2 (Weeks 27-52): 62 PM
├─ Lead Thermo Eng: 14 PM
├─ Lead ML/AI Sci: 12 PM
├─ Data Engineer: 9 PM
├─ Software Architect: 10 PM
└─ Supporting: 17 PM

MS-3 (Weeks 53-78): 92 PM (PEAK EFFORT)
├─ Lead Thermo Eng: 18 PM
├─ Lead ML/AI Sci: 16 PM
├─ Software Architect: 16 PM
├─ Data Engineer: 14 PM
├─ QA Lead: 12 PM
└─ Junior Engineers: 16 PM

MS-4 (Weeks 79-130): 82 PM
├─ Lead ML/AI Sci: 18 PM
├─ Data Engineer: 14 PM
├─ Software Architect: 16 PM
├─ QA Lead: 18 PM
└─ Supporting: 16 PM

MS-5 (Weeks 131-156): 38 PM (WIND-DOWN)
├─ Lead Thermo Eng: 10 PM
├─ Lead ML/AI Sci: 8 PM
├─ Project Manager: 8 PM
└─ Supporting: 12 PM
```

---

## SECTION 14: KEY DATES & MILESTONES

### Milestone Review Dates (Fixed)

| Milestone | Review Date | Duration | Key Reviewers | Approval Authority |
|-----------|------------|----------|---------------|-------------------|
| **Kickoff** | Week 1, Day 1 | 4 hours | PM, Lead Roles, DRDO | Program Director |
| **MS-1 PDR** | Week 26 (end) | 2-3 days | All team, DRDO Committee | DRDO Director + Committee |
| **Design Review** | Week 39 (mid-MS-2) | 1 day | Tech leads, DRDO | DRDO Technical Lead |
| **MS-2 CDR** | Week 52 (end) | 2-3 days | All team, DRDO Committee | DRDO Director + Committee |
| **Prototype Review** | Week 65 (mid-MS-3) | 1 day | QA, Tech leads | DRDO Quality Rep |
| **MS-3 CDR** | Week 78 (end) | 2-3 days | All team, DRDO Committee | DRDO Director + Committee |
| **SIR (System Integration)** | Week 78 (end) | 1 day | Architects, QA, DRDO | DRDO Systems Lead |
| **ATP Readiness** | Week 109 (mid-MS-4) | 1 day | QA, PM, DRDO | DRDO ATP Lead |
| **MS-4 ATP Execution** | Weeks 109-124 | 4 weeks on-site | ATP Committee, Industry | DRDO ATP Committee |
| **MS-5 Completion** | Week 156 (end) | 1-2 days | All team, DRDO | DRDO Director |

---

## SECTION 15: CONTINGENCY & BUFFER ALLOCATION

### Schedule Buffers Integrated into Plan

| Buffer Type | Location | Duration | Justification |
|-------------|----------|----------|---------------|
| **SRD Finalization Buffer** | Between W11-W18 | 2 weeks | Requirement iterations with DRDO |
| **Design Buffer** | Between W45-W52 | 3 weeks | Design optimization, stakeholder reviews |
| **Prototype Integration Buffer** | Between W70-W78 | 2 weeks | Unforeseen integration issues |
| **ATP Execution Buffer** | Between W109-W124 | 6 weeks | High variability with DRDO testing |
| **Documentation Buffer** | Between W140-W150 | 2 weeks | Final polish, review cycles |
| **Overall Project Contingency** | Spread across all phases | 3.6 months (10%) | Risk mitigation allocation |

---

## SECTION 16: RESOURCE AVAILABILITY & CROSS-TRAINING

### Cross-Training Matrix (Critical Knowledge Preservation)

| Primary Role | Backup Resource | Criticality | Training Duration |
|-------------|-----------------|------------|------------------|
| **Project Manager** | Systems Engineer | Critical | 4 weeks |
| **Lead Thermo Eng** | Junior Thermo Eng #1 | High | 8 weeks |
| **Lead ML/AI Sci** | ML Engineer #1 | High | 8 weeks |
| **Software Architect** | Lead Soft Eng #1 | High | 6 weeks |
| **Data Engineer** | Data Scientist | Medium | 6 weeks |
| **QA Lead** | QA Engineer #1 | High | 6 weeks |

### Leave/Absence Planning

- Monthly team meetings for capacity planning
- 2 weeks annual leave per team member (staggered)
- No critical single-point-of-failure (SPOF) roles
- Cross-team knowledge documentation quarterly

---

## SECTION 17: METRICS & TRACKING

### Weekly Tracking Metrics (Weeks 1-26)

| Metric | Target | Tracking Frequency |
|--------|--------|-------------------|
| Schedule Variance (SV) | ≤±3 days/week | Weekly |
| Effort Variance (EV) | ±5% vs. plan | Weekly |
| Risk Status | <5 open high risks | Weekly |
| Deliverable Quality | 0 critical defects | Weekly |
| DRDO Feedback Resolution | <5 days | On-demand |

### Monthly Tracking Metrics (Weeks 27-156)

| Metric | Target | Tracking Frequency |
|--------|--------|-------------------|
| Milestone Progress | On Schedule ±2 weeks | Monthly |
| Budget Variance | ±5% | Monthly |
| Resource Utilization | 85-95% | Monthly |
| Risk Trend | Decreasing or stable | Monthly |
| Stakeholder Satisfaction | >3.5/5 | Quarterly |

---

## SECTION 18: DEPENDENCY MAP & CRITICAL PREDECESSORS

### High-Impact Dependencies

```
W1-W4: Project Initiation (Foundation)
  ↓
W5-W18: Requirements & SRD (Gating all design)
  ↓
W6-W22: Tech Survey & Architecture (Parallel with SRD)
  ↓
W19-W26: PDD Finalization & PDR (Gate to MS-2)
  ↓
W27-W52: Detailed Design (Gate to MS-3)
  ↓
W53-W78: Prototype Implementation & Testing (Gate to MS-4)
  ↓
W79-W130: Production & ATP (Gate to MS-5)
  ↓
W131-W156: Documentation & ToT (Project Closure)
```

---

## SECTION 19: RESOURCE COST TRACKING (36-MONTH PROJECT)

### Cumulative Monthly Cost Forecast

| Month | Phase | Avg FTE | Monthly Cost (INR) | Cumulative Cost (INR) | % of Total Budget |
|-------|-------|---------|-------------------|----------------------|------------------|
| M1-M3 | MS-1 | 6 FTE | ₹20,00,000 | ₹60,00,000 | 1.3% |
| M4-M6 | MS-1 | 8 FTE | ₹28,00,000 | ₹1,44,00,000 | 3.2% |
| M7-M12 | MS-2 | 12 FTE | ₹42,00,000 | ₹3,96,00,000 | 8.8% |
| M13-M18 | MS-3 | 16 FTE | ₹56,00,000 | ₹7,32,00,000 | 16.3% |
| M19-M24 | MS-4 | 14 FTE | ₹49,00,000 | ₹10,26,00,000 | 22.8% |
| M25-M30 | MS-4 | 14 FTE | ₹49,00,000 | ₹13,20,00,000 | 29.3% |
| M31-M36 | MS-5 | 10 FTE | ₹35,00,000 | ₹15,30,00,000 | 34.0% |
| **TOTAL PROJECT** | **All** | **14 FTE avg** | **-** | **₹15.30 Cr (approx. ₹15.00 Cr)** | **100%** |

---

## SECTION 20: RISK-ADJUSTED SCHEDULE (WITH CONTINGENCY)

### Schedule Risk Events & Buffers

| Risk Event | Probability | Impact | Built-in Buffer | Contingency Action |
|-----------|-------------|--------|-----------------|-------------------|
| PDR delays (DRDO) | 30% | 2-4 weeks | 2 weeks in W19-W26 | Prepare multiple SRD versions early |
| Data access delays | 40% | 3-6 weeks | 4 weeks in W27-W38 | Use synthetic/historical data initially |
| Hardware procurement delays | 25% | 4-8 weeks | 4 weeks in W79-W90 | Order immediately post-CDR |
| Prototype rework | 50% | 2-4 weeks | 2 weeks in W70-W78 | Iterative design validation early |
| ATP delays | 60% | 4-8 weeks | 6 weeks in W109-W124 | Pre-ATP testing, clear criteria |
| **Total Schedule Contingency** | | | **3.6 months** | Spread across all phases |

---