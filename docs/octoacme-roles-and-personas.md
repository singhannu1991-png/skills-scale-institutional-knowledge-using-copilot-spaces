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

## Quality Assurance / Testing Lead

### Role Summary
QA Leads define quality standards, own test strategies, and validate that features meet acceptance criteria before release. They collaborate with product and engineering to ensure comprehensive testing coverage and reduce post-release defects.

### Responsibilities
- Define and maintain test plans and QA strategy
- Establish and communicate quality acceptance criteria
- Execute manual testing and review automated test coverage
- Identify and document defects with clear reproduction steps
- Participate in definition of done discussions
- Validate production releases and smoke tests
- Review test coverage during code review and pull request assessment

### Goals
- Ensure features meet acceptance criteria before shipment
- Reduce post-release defects and improve customer experience
- Maintain high test coverage with balanced automation and manual testing
- Accelerate delivery cycles through efficient quality gates

### Typical Communication
- Sprint planning and retrospectives
- Test case reviews with developers and product
- Defect triage and severity assessment
- Pre-release validation sign-off
- Quality metrics and coverage reporting

### Interactions
- **With Developers**: Collaborates on test coverage during code review; provides rapid feedback on PRs; partners on automation strategy
- **With Product Managers**: Validates acceptance criteria are testable; raises concerns about coverage gaps; advises on quality trade-offs
- **With Project Managers**: Reports quality metrics and risks; flags test readiness blockers; coordinates release validation
- **With Technical Leads**: Reviews test strategy for complex components; discusses automation approach for architectural changes

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide architectural decisions, conduct design reviews, and ensure technical solutions are scalable, secure, and aligned with system standards. They enable developers to ship high-quality code efficiently while reducing technical debt.

### Responsibilities
- Drive technical design discussions and architecture reviews
- Conduct code reviews for architectural and design patterns
- Identify technical risks and propose mitigations
- Mentor developers on best practices and design patterns
- Ensure consistency across services and components
- Collaborate on estimating and breaking down complex technical work
- Document architecture decisions (ADRs) and maintain system diagrams

### Goals
- Maintain system scalability, security, and maintainability
- Reduce technical debt through proactive architecture guidance
- Enable fast, confident delivery of features
- Foster a culture of technical excellence and knowledge sharing

### Typical Communication
- Design review meetings before implementation
- Code review comments on PRs focusing on patterns and arch consistency
- Technical design docs for complex features
- Architecture decision records (ADRs)
- Mentoring sessions and knowledge sharing

### Interactions
- **With Developers**: Reviews designs and PRs; mentors on patterns and best practices; unblocks technical questions
- **With Product Managers**: Advises on technical feasibility and trade-offs during prioritization; communicates architectural constraints
- **With QA**: Collaborates on test strategy for complex components; advises on edge cases and integration points
- **With DevOps**: Ensures deployability and observability are designed in; aligns on infrastructure requirements

---

## Designer / UX Lead

### Role Summary
Designers define user experience, establish design system standards, and ensure products are intuitive and accessible. They collaborate with product and engineering to translate user needs into delightful, usable interfaces.

### Responsibilities
- Define user experience flows and interaction patterns
- Establish and maintain design system and component library
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Review implementation for design fidelity and accessibility
- Advise on usability and accessibility standards (WCAG, etc.)
- Mentor developers and QA on design principles

### Goals
- Deliver intuitive, accessible user experiences
- Maintain consistency across the product
- Reduce user friction and improve adoption
- Enable rapid iteration through design system reuse

### Typical Communication
- Design reviews and critique sessions
- User research findings and insights
- Design specifications and component documentation
- Accessibility and usability guidelines
- Feedback on implementation fidelity

### Interactions
- **With Product Managers**: Translates user needs into design; validates designs against product strategy
- **With Developers**: Collaborates on implementation details; reviews code for design system adherence
- **With QA**: Partners on usability and accessibility testing; advises on acceptance criteria for UX features

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps Engineers own deployment pipelines, infrastructure provisioning, and production readiness. They ensure reliable, secure, and observable deployments that enable teams to ship with confidence.

### Responsibilities
- Maintain CI/CD pipelines and infrastructure-as-code
- Manage staging and production environments
- Design and implement deployment strategies
- Establish monitoring, alerting, and observability standards
- Conduct security scanning and infrastructure compliance checks
- Execute deployments and coordinate rollbacks if needed
- Provide runbooks and incident response playbooks

### Goals
- Enable fast, reliable, and secure deployments
- Minimize downtime and deployment-related incidents
- Ensure system observability and rapid issue diagnosis
- Automate toil and enable team self-service

### Typical Communication
- Release planning and deployment scheduling
- Infrastructure requirement discussions during planning
- Post-incident retrospectives and blameless reviews
- Metrics and observability dashboards
- On-call handoff notes and incident summaries

### Interactions
- **With Developers**: Advises on deployment requirements; partners on CI/CD troubleshooting; reviews infrastructure code
- **With QA**: Ensures staging environment matches production; coordinates smoke test execution and validation
- **With Project Managers**: Communicates deployment windows and readiness status; escalates infrastructure risks
- **With Technical Leads**: Aligns on architectural requirements for deployability; designs observability into systems

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove process blockers, and coach teams on agile practices. They enable teams to be self-organizing, transparent, and continuously improving.

### Responsibilities
- Facilitate sprint planning, standups, retrospectives, and reviews
- Track sprint velocity and burndown metrics
- Help team remove blockers and impediments
- Coach team on agile practices and ceremonies
- Manage sprint backlog and story workflow
- Facilitate communication between team and stakeholders
- Promote continuous improvement and experimentation

### Goals
- Enable team autonomy and self-organization
- Increase sprint velocity and predictability
- Foster psychological safety and continuous learning
- Reduce process friction and overhead

### Typical Communication
- Daily standup facilitation
- Sprint planning and retrospective meetings
- One-on-ones with team members
- Velocity and burndown metrics
- Escalation of process impediments to Project Manager

### Interactions
- **With Project Managers**: Escalates process blockers; provides team velocity and capacity insights
- **With Developers**: Removes team impediments; facilitates ceremonies; coaches on estimation and DoD
- **With Product Managers**: Manages backlog workflow; facilitates story refinement and prioritization
- **With All Roles**: Promotes psychological safety and continuous improvement culture

---

## Stakeholder / Sponsor

### Role Summary
Sponsors provide strategic direction, business context, and approval authority. They represent business interests and ensure projects align with organizational priorities and goals.

### Responsibilities
- Define business goals and success criteria
- Provide strategic direction and context
- Approve project scope, timeline, and resource allocation
- Make key trade-off and prioritization decisions
- Communicate business updates to leadership
- Remove organizational blockers and impediments
- Validate delivered outcomes against business objectives

### Goals
- Ensure projects deliver business value
- Align delivery with strategic priorities
- Minimize risk to business outcomes
- Enable team focus through clear direction

### Typical Communication
- Kick-off and go/no-go meetings
- Monthly stakeholder updates
- Executive briefings and business reviews
- Decision meetings on scope and trade-offs
- Post-release validation and retrospectives

### Interactions
- **With Project Managers**: Reviews project health and risks; makes prioritization and trade-off decisions
- **With Product Managers**: Aligns on business goals and success metrics; prioritizes roadmap
- **With All Roles**: Sets strategic context; removes organizational blockers; validates business outcomes

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the [Roles Interaction Matrix](roles-interaction-matrix.md) to understand how roles collaborate and hand off work.
- Use the [Role-Based Onboarding Checklist](role-based-onboarding-checklist.md) to help new team members quickly understand their responsibilities and key stakeholder relationships.
