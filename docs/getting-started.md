# CursorRIPER Direct - Getting Started

Welcome to CursorRIPER Direct, a streamlined, task-oriented framework for AI-assisted software development in Cursor IDE. This guide will help you get started quickly.

## What is CursorRIPER Direct?

CursorRIPER Direct (CRD) is a minimalist implementation of the RIPER methodology (Research, Innovate, Plan, Execute, Review) designed to enhance your development workflow with Cursor IDE's AI assistant. Unlike more complex frameworks, CRD focuses on:

- **Task completion** rather than framework components
- **Minimal documentation** that evolves with your project
- **Practical workflows** adapted to different development activities
- **Progressive detail** that starts simple and adds complexity only when needed

```mermaid
flowchart LR
    R[Research<br>Understand] --> I[Innovate<br>Explore]
    I --> P[Plan<br>Design]
    P --> E[Execute<br>Implement]
    E --> Rev[Review<br>Validate]
    Rev -.-> R
    
    style R fill:#e6f3ff,stroke:#0066cc
    style I fill:#e6ffe6,stroke:#006600
    style P fill:#fff0e6,stroke:#cc6600
    style E fill:#ffe6e6,stroke:#cc0000
    style Rev fill:#f0e6ff,stroke:#6600cc
```

## Installation

1. **Copy the framework files to your project**

   ```bash
   mkdir -p .cursor/rules
   cp -r /path/to/CursorRIPER-Direct/src/.cursor/rules/* .cursor/rules/
   ```

2. **Create the memory bank**

   ```bash
   mkdir -p memory-bank
   cp -r /path/to/CursorRIPER-Direct/src/templates/memory-bank/* memory-bank/
   ```

3. **Customize the memory files**

   Edit the files in your `memory-bank` directory to reflect your project:
   - `project.md`: Project overview, goals, requirements
   - `architecture.md`: Technical decisions, patterns, structure
   - `progress.md`: Work tracking, task status
   - `notes.md`: Developer context, setup instructions

## Project Initialization

If you're starting a new project, initialize it with:

```
/init
```

or

```
INITIALIZE PROJECT
```

The AI assistant will guide you through a streamlined setup process:
1. Gathering basic project information
2. Setting up project structure
3. Creating memory bank files
4. Beginning development

## Using the RIPER Workflow

CursorRIPER Direct uses five operational modes, each with a specific purpose:

### 1. RESEARCH Mode

Purpose: Understand the problem and existing code.

```
/research
```

Example prompt:
```
I need to understand how the authentication system works in this codebase.
```

### 2. INNOVATE Mode

Purpose: Explore potential solutions and approaches.

```
/innovate
```

Example prompt:
```
Let's brainstorm different ways we could implement the user notification system.
```

### 3. PLAN Mode

Purpose: Create detailed implementation specifications.

```
/plan
```

Example prompt:
```
Create a plan for implementing the shopping cart feature based on our discussions.
```

### 4. EXECUTE Mode

Purpose: Implement the approved plan.

```
/execute
```

Example prompt:
```
Let's implement the plan we created for the shopping cart feature.
```

### 5. REVIEW Mode

Purpose: Validate implementation against the plan.

```
/review
```

Example prompt:
```
Review the implementation of the shopping cart feature against our plan.
```

## Maintaining the Memory Bank

The memory bank is the heart of CursorRIPER Direct, providing persistent context across sessions:

1. **Regular Updates**: The AI will automatically update memory files at appropriate times
2. **Manual Updates**: You can request specific updates at any time
3. **Progressive Detail**: Start simple and add detail as your project evolves
4. **Visual Elements**: Use diagrams, emojis, and formatting to enhance clarity

To manually update a memory file, simply ask:

```
Please update the progress.md file to reflect that we've completed the login feature.
```

## Tips for Success

1. **Start Small**: Begin with basic information and add detail as needed
2. **Focus on Tasks**: Use the framework to complete development tasks, not to maintain the framework itself
3. **Be Explicit**: When transitioning modes, use clear commands (/research, /innovate, etc.)
4. **Keep Memory Current**: Regularly update memory files to maintain accurate context
5. **Adapt the Process**: Modify the workflow to fit your specific needs

## Next Steps

- Read the [Workflows Guide](workflows.md) for detailed information on using each mode
- Check the [Reference Guide](reference.md) for complete framework documentation
- Visit the [CursorRIPER Direct GitHub Repository](https://github.com/username/CursorRIPER-Direct) for updates and examples

---

*CursorRIPER Direct: Minimal framework, maximum productivity.*