```markdown
# 🚀 Karo's Implementation Plan for PRD: [PRD Title]. (Enhanced Edition, 228 lines). 

Feel free to reuse with credit (https://karozieminski.substack.com/).

## 0. Meta
- **Linked PRD:** [Insert link or reference to PRD doc]
- **Plan Version/Date:** YYYY-MM-DD
- **Plan Owner:** Name & Role
- **Stakeholders:** Names & Roles

---

## Project Context
*One-paragraph overview of the feature or product, the problem it solves, and its intended impact on users and the business. Include relevant background so that anyone opening this document can quickly understand scope and purpose.*

---

## 1. Objective
**Purpose:** Translate the PRD into a clear, execution-ready sequence for engineering, design, QA, and go-to-market teams.  
**Success Definition:** Plan is considered complete when all phases are executed, KPIs are met or exceeded, risks are mitigated, and learnings are documented.

**Example KPIs:**
- Adoption rate: XX% within 30 days of launch
- Uptime: ≥ 99.9% in first month
- Accessibility compliance: 100% WCAG 2.1 AA
- Customer satisfaction score: ≥ 8/10 post-launch survey

---

## 2. Readiness Checklist (Pre–Phase 1)
✅ All stakeholders identified and confirmed  
✅ Tools, repositories, and environments ready  
✅ Dependencies documented and owners assigned  
✅ PRD is complete, accessible, and version-controlled  
✅ Decision Log is linked and empty (ready for entries)  

---

## 3. Phase Breakdown

### Phase 1 – Discovery & Alignment
**Timeline:** [Start → End]  
**Goals:**
- Review PRD with all stakeholders
- Resolve **Open Questions** & confirm assumptions
- Validate feasibility & dependencies

**Tasks:**
1. Stakeholder walkthrough of PRD
2. Confirm **Goals & Non-Goals**
3. Sign off on **Requirements** and **Acceptance Criteria**
4. Assign functional owners

**Outputs:**
- Signed-off PRD
- Finalized scope & timeline
- Updated assumptions log

**Responsible:** PM, Tech Lead, Design Lead

---

### Phase 2 – Design & Technical Planning
**Timeline:** [Start → End]  
**Goals:**
- Produce final UX/UI designs
- Detail technical architecture
- Identify integration & API needs

**Tasks:**
1. Create wireframes & hi-fidelity mockups (UX team)
2. Finalize **Accessibility checklist (WCAG)**
3. Draft architecture & data schema changes
4. Confirm infrastructure, tooling, and integration requirements

**Outputs:**
- Approved design specs
- Approved technical design doc

**Responsible:** Design Lead, Tech Lead

---

### Phase 3 – Development
**Timeline:** [Start → End]  
**Goals:**
- Build features according to PRD requirements
- Maintain AI-safe, testable deliverables

**Tasks:**
1. Set up feature branches & environments
2. Implement **Functional Requirements**
3. Implement **Non-Functional Requirements**
4. Write unit/integration/E2E tests
5. Perform **Accessibility testing**
6. Pre-QA self-check by engineers against acceptance criteria

**Outputs:**
- Feature-complete code in staging
- Passing test suite

**Responsible:** Engineering Team

---

### Phase 4 – QA, Safety & Verification
**Timeline:** [Start → End]  
**Goals:**
- Validate deliverables against PRD & **Quality Check Report**
- Ensure operational safety and privacy compliance

**Tasks:**
1. QA tests each acceptance criterion (Gherkin-based)
2. Re-run **Karo’s Quality Checks**
3. Re-run **AI Gap Scan** to ensure no regressions *(see AI Gap Scan SOP)*
4. Conduct security, privacy, and performance testing
5. Execute rollback procedure drill

**Outputs:**
- QA sign-off
- AI Gap Report updated
- Rollback plan tested

**Responsible:** QA Lead, PM

---

### Phase 5 – Rollout & Monitoring
**Timeline:** [Start → End]  
**Goals:**
- Deploy feature with minimal disruption
- Monitor KPIs & risk areas in real time

**Tasks:**
1. Release via **Rollout Plan** (feature flags/phased)
2. Publish internal & external comms (per GTM checklist)
3. Monitor metrics, logs, and user feedback
4. Rapidly address issues
5. Execute rollback if critical issues are found

**Outputs:**
- Live feature
- Post-launch metrics dashboard

**Responsible:** PM, Engineering, Marketing/Comms

---

### Phase 6 – Post-Launch Review
**Timeline:** [Start → End]  
**Goals:**
- Evaluate feature success against PRD metrics
- Capture learnings & decision history

**Tasks:**
1. Compare actual results to **Metrics & Success Criteria**
2. Document changes from plan
3. Integrate customer feedback into retrospective
4. Update **Decision Log** & **Glossary**
5. Archive PRD & Plan in knowledge base

**Outputs:**
- Retrospective document
- Updated product roadmap

**Responsible:** PM, Data Analyst

---

### Phase 7 – Decommission/Sunset (If Applicable)
**Timeline:** [Start → End]  
**Goals:**
- Retire feature without user disruption
- Preserve knowledge for future projects

**Tasks:**
1. Communicate retirement plan internally & externally
2. Remove or disable related code and infrastructure
3. Update documentation and support materials

**Outputs:**
- Decommissioning report
- Archived assets

**Responsible:** PM, Tech Lead

---

## 4. RACI Matrix
| Deliverable              | Responsible | Accountable | Consulted | Informed |
|--------------------------|-------------|-------------|-----------|----------|
| PRD Sign-off              | PM          | PM          | Eng, Design | Execs    |
| UX/UI Design              | Design Lead | Design Lead | PM, Eng   | QA       |
| Architecture              | Tech Lead   | Tech Lead   | PM, DevOps| Execs    |
| Development               | Engineers   | Tech Lead   | PM, QA    | All      |
| QA & AI Gap Scan          | QA Lead     | QA Lead     | PM, Eng   | All      |
| Rollout                   | PM          | PM          | Eng, Marketing | All  |
| Post-Launch Review        | PM          | PM          | Eng, Data | All      |
| Decommission              | PM          | PM          | Eng, Support | All   |

---

## 5. Risk Register
| Risk ID | Description | Severity (L×I) | Owner | Mitigation |
|---------|-------------|----------------|-------|------------|
| R1      | Key API dependency delayed | 4×5 = 20 (High) | Tech Lead | Parallelize integration testing |

---

## 6. Change Management
- All changes to scope/timeline must be logged in **Decision Log** of PRD.
- Evaluate trade-offs before scope changes (impact on KPIs, dependencies, risks).
- Changes require stakeholder sign-off before implementation.

---

## 7. References
- Linked PRD (latest version)
- Related design docs
- Linked analytics dashboards
- Support runbooks
- AI Gap Scan SOP
- GTM Launch Playbook

---

## 8. Version History
| Date       | Version | Changes | Author |
|------------|---------|---------|--------|
| YYYY-MM-DD | 1.0     | Initial draft | PM   |
```
