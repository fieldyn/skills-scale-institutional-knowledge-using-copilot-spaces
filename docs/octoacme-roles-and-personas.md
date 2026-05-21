# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Test Engineers

### Role Summary
QA / Test Engineers ensure deliverables meet acceptance criteria and quality expectations before release.

### Responsibilities
- Define test strategy for stories, features, and releases
- Create and execute test plans (manual, automated, smoke)
- Track and triage defects with Developers and PMs
- Validate Definition of Done quality gates
- Provide release readiness input based on test evidence

### Goals
- Reduce escaped defects and production regressions
- Increase confidence in releases
- Improve traceability from requirements to validation

### Typical Communication
- Test plans and defect reports in shared tracking tools
- Daily triage with Developers
- Release go/no-go input with PM and Release Manager

### Interactions with existing roles
- **Developers:** align on reproducible defects and fixes
- **Product Managers:** confirm acceptance criteria interpretation
- **Project Managers:** communicate quality risk and test status

---

## Technical Leads / Engineering Leads

### Role Summary
Technical Leads provide technical direction, reduce implementation risk, and support high-quality execution.

### Responsibilities
- Own architecture and key technical decisions
- Guide estimation feasibility and technical sequencing
- Review complex PRs and design proposals
- Identify and mitigate technical risks and dependencies
- Mentor Developers and promote engineering standards

### Goals
- Keep architecture maintainable and scalable
- Reduce technical uncertainty early
- Improve delivery predictability and code quality

### Typical Communication
- Design reviews and architecture decision records
- Implementation risk reviews with PM and PdM
- Technical syncs with Developers and QA

### Interactions with existing roles
- **Developers:** unblock implementation and review critical changes
- **Product Managers:** evaluate scope/priority trade-offs
- **Project Managers:** align technical sequencing with delivery plans

---

## Operations / Release Managers

### Role Summary
Operations / Release Managers coordinate release readiness, deployment execution, and post-release verification.

### Responsibilities
- Plan release windows and deployment sequencing
- Confirm release checklist completion and approvals
- Coordinate rollout, monitoring, and rollback readiness
- Publish release communications to stakeholders and support
- Capture release metrics and follow-up actions

### Goals
- Deliver safe, predictable releases
- Minimize deployment risk and downtime
- Improve release transparency and incident readiness

### Typical Communication
- Release readiness updates and go/no-go checkpoints
- Deployment timeline communications across teams
- Post-release status and incident follow-up

### Interactions with existing roles
- **Developers:** confirm deployability and rollback steps
- **Project Managers:** align release timeline with project milestones
- **Product Managers:** validate release scope and customer impact

---

## Stakeholders / Sponsors

### Role Summary
Stakeholders / Sponsors provide business context, strategic alignment, and approvals for key project decisions.

### Responsibilities
- Validate business outcomes and strategic fit
- Approve major scope, timeline, or budget decisions
- Resolve cross-team priority conflicts at escalation points
- Provide feedback on milestone demos and outcomes

### Goals
- Ensure work aligns with business priorities
- Improve decision speed for high-impact trade-offs
- Maximize return on delivery investments

### Typical Communication
- Milestone reviews and steering updates
- Escalation decisions for business-impacting blockers
- Outcome reviews tied to success metrics

### Interactions with existing roles
- **Product Managers:** align outcomes and prioritization
- **Project Managers:** review status, risk, and decisions requiring sponsorship
- **Developers:** provide domain context during key reviews when needed

---

## Support / Customer Success

### Role Summary
Support / Customer Success represents customer impact during planning and after release.

### Responsibilities
- Provide customer issue trends and feedback themes
- Validate operational readiness (known issues, support notes)
- Communicate release impacts and workarounds to customers
- Feed production insights into backlog prioritization

### Goals
- Reduce customer-facing friction
- Improve responsiveness to real-world usage issues
- Strengthen the feedback loop between delivery and operations

### Typical Communication
- Weekly customer signal summaries
- Incident/customer-impact updates during releases
- Priority feedback to PdM and PM during planning

### Interactions with existing roles
- **Product Managers:** translate customer signals into roadmap input
- **Project Managers:** align support readiness to release plans
- **Developers:** relay production pain points and defect impact

---

## Security / Compliance Reviewers

### Role Summary
Security / Compliance Reviewers ensure delivery meets security controls, regulatory obligations, and risk tolerance.

### Responsibilities
- Review threats, controls, and security requirements
- Validate compliance-related acceptance criteria
- Confirm remediation plans for identified vulnerabilities
- Support release readiness with security sign-off where required
- Participate in incident postmortems for control improvements

### Goals
- Reduce security and compliance risk
- Integrate security earlier in planning and delivery
- Improve auditability of security-related decisions

### Typical Communication
- Security review findings and mitigation recommendations
- Compliance checkpoint outcomes for affected features
- Release approvals/conditions for security-sensitive changes

### Interactions with existing roles
- **Developers:** guide secure implementation and remediation
- **Product Managers:** align control requirements with scope decisions
- **Project Managers:** track security dependencies and escalation timelines

---

## Role participation by project phase

| Role | Initiation | Planning | Execution | Release | Retrospective |
| --- | --- | --- | --- | --- | --- |
| Product Manager | **Lead** | **Lead** | Partner | Partner | Partner |
| Project Manager | Partner | **Lead** | **Lead** | Partner | **Lead** |
| Developers | Consulted | Partner | **Lead** | Partner | Partner |
| QA / Test Engineer | Consulted | Partner | Partner | **Lead** | Partner |
| Technical Lead / Engineering Lead | Partner | Partner | Partner | Consulted | Partner |
| Operations / Release Manager | Informed | Consulted | Partner | **Lead** | Consulted |
| Stakeholder / Sponsor | **Lead** | Partner | Informed | Consulted | Partner |
| Support / Customer Success | Consulted | Consulted | Partner | Partner | **Lead** |
| Security / Compliance Reviewer | Consulted | Partner | Partner | Partner | Consulted |

### Accountability notes
- Each phase should have one explicit owner for decisions and one backup owner.
- Capture ownership in kickoff notes and update when staffing changes.
- Use this matrix during onboarding and escalation to reduce handoff ambiguity.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
