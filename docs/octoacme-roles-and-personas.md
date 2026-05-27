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

## QA / Testing

### Role Summary
QA and Testing team members validate that delivered software meets quality standards, acceptance criteria, and user expectations. They work across the delivery lifecycle to prevent defects and ensure release readiness.

### Responsibilities
- Define and execute test plans, test cases, and regression suites
- Validate features against acceptance criteria and edge cases
- Report, triage, and track defects to resolution
- Participate in sprint planning to assess testability of requirements
- Support release readiness decisions with sign-off and quality metrics

### Goals
- Ensure high-quality, defect-free releases
- Reduce the cost of defects by catching issues early
- Build confidence in the team's ability to ship reliably

### Typical Communication
- Test results and defect reports shared with Developers and Project Manager
- Participation in sprint reviews and release readiness meetings
- Ad-hoc coordination with Developers on defect reproduction

### Interactions with Existing Roles
- **Developers**: pair on defect triage and confirm fixes; review acceptance criteria together during planning
- **Product Managers**: clarify expected behavior and edge cases for features
- **Project Managers**: escalate release-blocking issues; contribute quality status to weekly reports
- **Stakeholders**: communicate overall quality posture ahead of releases

---

## UX Designer

### Role Summary
UX Designers drive usability research, wireframing, and prototyping to ensure delivered solutions genuinely meet user needs. They bridge the gap between user insight and technical implementation.

### Responsibilities
- Conduct user research, usability tests, and heuristic evaluations
- Create wireframes, mockups, and interactive prototypes
- Define and maintain design systems and style guides
- Review implemented features for design fidelity
- Advocate for accessibility and inclusive design practices

### Goals
- Deliver intuitive, user-centred experiences
- Reduce rework caused by late-stage usability issues
- Align design decisions with validated user needs and product goals

### Typical Communication
- Design reviews and prototype walkthroughs with Product Manager and Developers
- Usability research summaries shared with stakeholders
- Async feedback via design tools (e.g., Figma comments) and PR reviews

### Interactions with Existing Roles
- **Developers**: collaborate on component implementation and provide design specifications; review front-end work for design fidelity
- **Product Managers**: co-define user stories and acceptance criteria; share research findings to inform prioritization
- **Project Managers**: flag design dependencies and timeline constraints during planning
- **QA / Testing**: clarify intended UX behavior to support test-case definition

---

## Technical Writer

### Role Summary
Technical Writers create and maintain user-facing and internal documentation, ensuring teams and customers can understand, use, and contribute to the product effectively.

### Responsibilities
- Author, edit, and maintain user guides, API references, release notes, and internal process docs
- Collaborate with subject-matter experts to ensure accuracy and completeness
- Establish and enforce documentation standards and templates
- Review pull requests and release artifacts for documentation impact
- Keep documentation aligned with product releases and process changes

### Goals
- Make complex information clear and accessible to the intended audience
- Reduce support burden by providing self-service documentation
- Ensure documentation ships alongside features, not after them

### Typical Communication
- Regular syncs with Developers and Product Manager to stay ahead of upcoming changes
- Review cycles with QA to validate procedural accuracy
- Announcements to stakeholders when major documentation updates are published

### Interactions with Existing Roles
- **Developers**: gather technical details for API and integration docs; review code comments and inline documentation
- **Product Managers**: align documentation scope with the roadmap; incorporate user-research insights into content
- **Project Managers**: track documentation tasks in project plans; flag risks when doc work is under-resourced
- **QA / Testing**: validate that documented procedures are accurate and reproducible

---

## Scrum Master / Delivery Lead

### Role Summary
The Scrum Master / Delivery Lead facilitates agile processes, removes impediments, and ensures the team adheres to agreed workflows. They protect the team's capacity and foster a culture of continuous improvement.

### Responsibilities
- Facilitate sprint ceremonies: planning, daily standup, review, and retrospective
- Identify and actively resolve blockers and dependencies
- Coach the team on agile principles and process improvements
- Maintain and improve the team's ways of working
- Track and communicate team velocity, capacity, and delivery health

### Goals
- Enable the team to deliver predictably and sustainably
- Continuously improve team efficiency and morale
- Ensure agile practices are understood and consistently applied

### Typical Communication
- Daily standups and sprint ceremony facilitation
- Impediment logs and blockers escalated to Project Manager and leadership
- Retrospective action items tracked and followed up

### Interactions with Existing Roles
- **Developers**: remove day-to-day blockers; coach on agile practices and self-organization
- **Product Managers**: coordinate backlog refinement and sprint planning; protect team focus from scope changes mid-sprint
- **Project Managers**: align on delivery milestones, risks, and resource needs; share team capacity data
- **QA / Testing**: ensure testing is embedded in the sprint cycle and not deferred to a separate phase

---

## Release Manager

### Role Summary
Release Managers plan, coordinate, and communicate release schedules and activities. They ensure that releases are delivered safely, with appropriate stakeholder awareness and rollback readiness.

### Responsibilities
- Own and maintain the release calendar and cut-off schedules
- Coordinate release readiness across development, QA, and operations teams
- Manage release communications to internal and external stakeholders
- Oversee deployment checklists, go/no-go decisions, and rollback plans
- Track and document post-release incidents and feed learnings back into the process

### Goals
- Ship releases on schedule with minimal customer disruption
- Ensure all release activities are properly tracked and communicated
- Reduce release-related incidents through rigorous preparation

### Typical Communication
- Release readiness meetings with Developers, QA, and Project Manager
- Pre-release announcements and post-release summaries to stakeholders
- Incident communications during live deployments

### Interactions with Existing Roles
- **Developers**: confirm code freeze, deployment steps, and feature flags; review release notes
- **Product Managers**: align on feature scope and release messaging
- **Project Managers**: synchronize release dates with the broader project timeline and risk register
- **QA / Testing**: obtain quality sign-off and ensure release criteria are met before deploying

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a vested interest in the project's outcome. They provide strategic direction, funding, user insight, or partnership inputs, and must be kept informed and engaged throughout the lifecycle. Stakeholder types include:

- **Sponsor**: executive or business owner providing funding and strategic approval
- **End User**: the person who will ultimately use the delivered product or service
- **Partner**: an external organization or internal team whose work depends on or feeds into the project

### Responsibilities
- Provide clear requirements, priorities, and constraints at project initiation
- Review and approve key artifacts (charter, roadmap, release plan)
- Attend milestone demos and provide timely feedback
- Escalate concerns and decisions through agreed channels
- Support adoption, change management, and user communication as needed

### Goals
- See their needs and objectives reflected in delivered outcomes
- Stay informed without being overwhelmed by operational detail
- Provide input at the right moments to shape decisions effectively

### Typical Communication
- Monthly stakeholder updates (or milestone-based briefings) from the Project Manager
- Roadmap and release announcements from the Product Manager
- Escalation and decision requests as needed from PM or Project Manager

### Interactions with Existing Roles
- **Developers**: infrequent direct contact; may participate in sprint reviews or demos to provide feature feedback
- **Product Managers**: primary relationship for roadmap alignment, prioritization trade-offs, and outcome validation
- **Project Managers**: receive regular status updates, risk summaries, and decision requests; approve scope or timeline changes
- **QA / Testing**: may observe acceptance testing or user-acceptance testing (UAT) sessions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

