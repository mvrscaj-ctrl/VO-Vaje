# Risk Treatment Plan — Top 5 Risks
## Blue River Health Case Study

---

## Executive Summary

This document outlines the risk treatment strategies for the top 5 identified risks at Blue River Health. Each risk has been assessed for likelihood and impact, and specific mitigation strategies have been developed with defined controls, timelines, and ownership.

**Organization:** Blue River Health  
**Assessment Date:** 2026-03-08  
**Plan Period:** 12-18 months  
**Prepared by:** [Your Name]

---

## Risk Ranking Methodology

| Severity | Likelihood × Impact | Priority |
|----------|-------------------|----------|
| Critical | High × High | Immediate (0-3 months) |
| High | High × Medium OR Medium × High | Urgent (3-6 months) |
| Medium | Medium × Medium OR High × Low | Planned (6-12 months) |
| Low | Low × Any OR Any × Low | Ongoing |

---

## Risk #1: Ransomware Attack on Patient Database

### Risk Context
- **Asset at Risk:** Patient Database, EHR System
- **Current Vulnerability:** Flat network architecture, inconsistent patching, outdated backup system
- **Threat Actor:** External cybercriminals, opportunistic malware
- **Likelihood:** HIGH (exposed to widespread ransomware campaigns)
- **Impact:** CRITICAL (business disruption, data breach, regulatory penalties)
- **Risk Score:** 9/10 (CRITICAL)

### Risk Scenario
*If a ransomware infection occurs through phishing or unpatched vulnerability, exploiting the flat network architecture, then the organization will experience complete loss of patient data access, operational shutdown, financial loss, and potential regulatory violation.*

### Treatment Strategy: **MITIGATE**

| Element | Details |
|---------|---------|
| **Objective** | Reduce likelihood and impact of ransomware attack to acceptable levels |
| **Owner** | IT Director / Security Officer |
| **Budget Allocation** | €20,000 (Year 1) |

### Controls to Implement

#### Control 1.1: Network Segmentation
- **Description:** Isolate critical systems (EHR, patient database) into secure network segments
- **Type:** Technical
- **Implementation Phase:** Phase 1 (Immediate, 0-3 months)
- **Timeline:** 
  - Month 1-2: Design network architecture
  - Month 2-3: Implementation and testing
- **Responsible Party:** IT Manager + Network Engineer (external contractor)
- **Budget:** €8,000
- **Success Metrics:**
  - DMZ and patient data segment fully isolated
  - Cross-segment communication restricted to approved services
  - Zero unauthorized lateral movement attempts detected
- **Risk Reduction:** Limits ransomware spread to 1-2 systems instead of enterprise-wide

#### Control 1.2: Advanced Backup & Recovery System
- **Description:** Implement immutable, air-gapped backup solution with automated testing
- **Type:** Technical
- **Implementation Phase:** Phase 1 (Immediate, 0-3 months)
- **Timeline:**
  - Month 1: Requirements and vendor selection
  - Month 2-3: Setup and configuration
- **Responsible Party:** IT Operations Manager
- **Budget:** €12,000
- **Success Metrics:**
  - Full backup completion daily with 99.9% success rate
  - Monthly restore tests with <4 hour RTO
  - 3x copies maintained (on-site, off-site, cloud)
- **Risk Reduction:** Enables rapid recovery with minimal data loss

#### Control 1.3: Endpoint Detection & Response (EDR)
- **Description:** Deploy EDR software on all critical servers and workstations
- **Type:** Technical
- **Implementation Phase:** Phase 1 (Immediate, 0-3 months)
- **Timeline:**
  - Month 1: Pilot on 5 systems
  - Month 2-3: Full rollout to 85% of endpoints
- **Responsible Party:** Security Officer
- **Budget:** €6,000 (Year 1)
- **Success Metrics:**
  - 85% endpoint coverage with EDR
  - Threat detection alerts reviewed daily
  - <1 hour response time to detected threats
- **Risk Reduction:** Detects and blocks ransomware before encryption occurs

#### Control 1.4: Incident Response Plan & Tabletop Drill
- **Description:** Develop formal IR plan with ransomware playbook and conduct quarterly drills
- **Type:** Organizational
- **Implementation Phase:** Phase 1 (0-1 month)
- **Timeline:**
  - Week 1-2: Draft IR plan
  - Week 3: Approval and training
  - Month 2, 5, 8, 11: Quarterly tabletop exercises
- **Responsible Party:** Security Officer + IT Leadership
- **Budget:** €3,000
- **Success Metrics:**
  - Written IR plan with ransomware procedures
  - All staff trained on roles
  - Drill completion with <30 min breach notification achieved
- **Risk Reduction:** Minimizes response time and confusion during incident

### Implementation Timeline
