
# RAID Log – E-commerce Order Management

**Project:** E-commerce Order Management System  
**Document:** Risks, Assumptions, Issues, and Dependencies (RAID)  
**Status:** Illustrative project case study  
**Prepared by:** Sravan Jadala, IT Project Manager

> Note: This is a simulated portfolio example using fictional project information. It is not a record of confidential employer projects.

## 1. Purpose

The RAID log is used to identify, assess, track, and manage project risks, assumptions, issues, and dependencies throughout the project lifecycle.

It supports project governance, timely decision-making, stakeholder communication, and delivery planning.

## 2. Risk Register

| ID | Risk | Probability | Impact | Mitigation / Response | Owner | Status |
|---|---|---|---|---|---|---|
| R-01 | Third-party API integration may be delayed. | Medium | High | Confirm API specifications early, track vendor milestones, and maintain an escalation path. | Integration Lead | Open |
| R-02 | Requirements changes may affect the delivery timeline. | High | High | Establish change control, assess impacts, and obtain approval before incorporating scope changes. | Project Manager | Monitoring |
| R-03 | Performance issues may occur during peak order volumes. | Medium | High | Schedule load testing, review performance thresholds, and address bottlenecks before release. | QA Lead | Open |
| R-04 | Key resources may become unavailable during testing. | Medium | Medium | Confirm resource availability and identify backup resources for critical activities. | Project Manager | Monitoring |

## 3. Assumptions Register

| ID | Assumption | Validation Method | Owner | Status |
|---|---|---|---|---|
| A-01 | Business stakeholders will provide timely requirements approvals. | Confirm review timelines during project kickoff. | Business Lead | To Validate |
| A-02 | Required test environments will be available before SIT begins. | Confirm environment readiness with the technical team. | Technical Lead | To Validate |
| A-03 | External vendors will provide integration documentation and support. | Review vendor commitments and delivery dates. | Integration Lead | To Validate |
| A-04 | Business users will be available for UAT and sign-off. | Confirm UAT participants and schedule. | Business Lead | To Validate |

## 4. Issues Register

| ID | Issue | Impact | Action / Resolution Plan | Owner | Status |
|---|---|---|---|---|---|
| I-01 | Test data preparation is behind schedule. | May delay planned SIT execution. | Coordinate data requirements and agree on a revised preparation date. | QA Lead | In Progress |
| I-02 | Some requirements need further business clarification. | Could delay development and testing. | Arrange a requirements workshop and document approved decisions. | Business Analyst | Open |
| I-03 | Integration testing identified interface validation defects. | May affect end-to-end order processing. | Log defects, assign technical owners, and retest after fixes. | Technical Lead | In Progress |

## 5. Dependencies Register

| ID | Dependency | Required By | Impact if Delayed | Owner | Status |
|---|---|---|---|---|---|
| D-01 | External payment gateway API readiness | Integration Testing | Payment integration testing may be delayed. | Integration Lead | In Progress |
| D-02 | Test environment provisioning | SIT Start | System testing may not begin as planned. | Infrastructure Lead | Monitoring |
| D-03 | Business approval of requirements | Development Start | Development scope may remain unconfirmed. | Business Lead | In Progress |
| D-04 | UAT completion and business sign-off | Production Release | Go-live approval may be delayed. | Business Lead | Planned |

## 6. RAID Governance and Review

- Review open risks, issues, assumptions, and dependencies during weekly project status meetings.
- Assign a clear owner and target resolution date to each high-priority item.
- Escalate critical risks and blockers to the project sponsor or steering committee.
- Assess the impact of changes on scope, schedule, budget, resources, and quality.
- Update the RAID log after stakeholder discussions and project decisions.
- Track mitigation actions until closure and document decisions.

## 7. Escalation Criteria

Escalation is required when an item:

- Threatens a key milestone or the approved delivery timeline.
- Has a significant impact on scope, budget, quality, or customer experience.
- Cannot be resolved by the assigned owner within the agreed timeframe.
- Requires a decision or resources beyond the project team's authority.

## 8. Expected Outcome

The RAID log provides project stakeholders with a consolidated view of delivery uncertainties, current blockers, critical assumptions, and external dependencies. It supports proactive risk management, accountability, and informed project decisions.
