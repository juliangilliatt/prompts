<objective>
Your objective is to create a detailed Product Requirements Document (PRD) in Markdown format, based on what’s provided in the <context> below. The PRD should be clear, actionable, and suitable for a junior developer to understand and implement the feature.
</objective>

<context>

<product>
The idea/solution you want to build.
</product>

<background>
Copy the current state, target audience, and user stories from the output of the brainstorm-template.
</background>

<tech>
Current-tech-choices and/or preferences
Hosting:
Database:
Analytics:
Performance requirements:
Security:
</tech>
</context>

<output-format>
## Executive Summary
[Brief overview of the feature, key business objectives, expected impact on customers, etc.,.]

## Terminology
- [List of any terms used in this document that may be unfamiliar to readers.]

## Customer Problem
**Audience:** [Who are we targeting? Be very specific.]
**Current State Pain Points:**
- [What is the before state and associated pains?]
**Evidence:**
- [What evidence do we have that this is important for us to solve? (qual + quant data)]

## Objectives
- [What must become possible as a result of this work? What does the "after" state look like? How are we solving the pains? Why are we uniquely positioned to solve it? What is the ideal customer experience? What is the programmatic user experience?]

## Success Criteria
-  [What success looks like at a high level.]

## Key Features
- [Major features we are building as part of this project]

## Non-goals
- [Things we are explicitly NOT doing as part of this project.]

## User Narrative
[Story of a fictional user and what their experience is with the product after this new work is complete. This should help illustrate to readers the value of doing this work.]

## Engineering Goals
- [Things we are doing as part of this project.]

## Assumptions and Risks
### Assumptions
- [Things we're assuming to be true.]

### Risks
- [Things we know might be risky → And a mitigation plan.]

## Success Metrics
### Business Metrics:
- [KPIs to measure success]

### Usage Metrics:
- [Adoption and usage targets]

### Technical Metrics:
- [Performance benchmarks]

## Open Questions
- [Open question]
	- [How we might answer the question (e.g., survey users)]

## Appendix
### User Stories
#### Primary:
- [As a [user type], I want to [action] so that [benefit]]
- [Include at least 3-5 detailed user stories]

#### Secondary:
- [As a [user type], I want to [action] so that [benefit]]
- [Include at least 3-5 detailed user stories]

### User Journey and Experience
- [Describe how features are designed to support user needs and the product experience.]
- [Map out high-level, known, end-to-end user journeys or key task flows to ensure alignment with product goals and user needs.]
- [Screen or Interaction]
- [Description of different “states” of that screen]
- [How it handles state changes visually]
- [Animations, information architecture, progressive disclosure, visual hierarchy, etc.]

### Feature Requirements
- [Core user-facing feature requirements]

### Non-functional requirements (performance, security, etc.)
- **Performance**
	- [Performance requirements]
- **Scalability**
	- [Scalability requirements]
- **Security**
	- [Security requirements]
- **Accessibility**
	- [Accessibility requirements]

### Cost Analysis:
- [Costs associated with required vendors and technologies]

### Product UX Considerations

#### Information Architecture
```
[Information architecture (as needed)]
```

#### Visual Design Principles
- [Aesthetic, typography, accenting, spacing, etc.,)]

### Engineering Considerations
#### Tech Stack
- [Third-party tools, languages, etc.,]

#### Monitoring Strategy
- [Tools to monitor uptime, performance, traffic, etc.,]

#### Tool Dependencies
[Document any dependencies on third-party tools, clarifying their role within the user’s workflow. Identify and address gaps in the understanding of adjacent user workflows that could impact usability.]

#### Data Model
```
[As needed]
```

#### Admin Workflow:
- [As needed]

#### Accessibility and Usability
- [Highlight any core technical or complex concepts within the experience that may hinder user access, task performance, or understanding. Define qualitative and/or quantitative metrics to measure usability and effectiveness.]

### Launch Plan
- [Launch strategy (e.g., A/B test, phased rollout, etc.,)]
- [Communication plan]
- [Training requirements or enablement requirements for internal teams]
- [Major milestones]
- [Dependencies]

### How it Works
[A step-by-step user guide to using the new feature.]

### FAQ
1. Question 1
   Answer to question 1.

1. Question 2
 Answer to question 2.

1. Question N
Answer to question N.
</output-format>

<guidelines>
- Assume the primary reader of the PRD is a **junior developer**. Therefore, requirements should be explicit, unambiguous, and avoid jargon where possible. Provide enough detail for them to understand the feature's purpose and core logic.
- Do NOT start implementing the PRD
- Make sure to ask the user clarifying questions
- Take the user's answers to the clarifying questions and improve the plan
- Be ruthless in your critique of your first PRD
</guidelines>

<instructions>
1. Take on a collaborative/consultative role and ask clarifying questions to gather sufficient detail about what’s provided in the <context> below. The goal is to understand the "what" and "why" of the feature, not necessarily the "how" (which the developer will figure out). Each time the user responds back to you, you integrate their responses into the overall plan.
2. Based on the <context> below and the user's answers to the clarifying questions, generate a PRD using the structure outlined below.
3. Critique that PRD. What questions aren’t addressed? What risks aren’t identified? If the CEO read this, would he be fully bought in? Does this approach consider cohesion and interconnectedness with the existing product? Is the approach consistent with the broader product strategy?
4. Based on that critique, rewrite the PRD and present it using the <format> below.
</instructions>