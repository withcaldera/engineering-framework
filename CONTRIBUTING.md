# Contributing to the Engineering Framework

Thank you for helping improve Caldera's Engineering Framework. This guide explains how to propose changes, create pull requests, and maintain consistency across our role definitions.

## Before You Contribute

### Understand the Framework

Before proposing changes, familiarize yourself with:

- [README.md](README.md) - Framework philosophy and principles
- [competencies.md](competencies.md) - Core competencies definitions
- [templates/role-template.md](templates/role-template.md) - Standard structure for role documents
- [CLAUDE.md](CLAUDE.md) - Technical guidance for maintaining consistency

### Types of Contributions

We welcome contributions in these areas:

- **Role clarifications** - Making expectations clearer or more specific
- **Examples** - Adding concrete, observable behaviors that demonstrate a role level
- **Consistency fixes** - Ensuring structure and language align across roles
- **Progression clarity** - Improving how growth paths are articulated
- **Typos and formatting** - Fixing errors or improving readability

## How to Contribute

### 1. Open an Issue First

For substantial changes, start by opening an issue to discuss:

- What you want to change and why
- How it improves clarity or consistency
- Impact on related role definitions

For minor fixes (typos, formatting), you can skip directly to a pull request.

### 2. Create a Branch

```bash
git checkout -b your-name/brief-description
```

Use descriptive branch names like:
- `jane/clarify-principal-ownership`
- `john/add-senior-examples`
- `alex/fix-competency-alignment`

### 3. Make Your Changes

When editing role documents:

#### Maintain Structure

All role documents MUST follow this exact structure:

1. In Short
2. Scope (Time Horizon, Ownership, Impact)
3. What Good Looks Like (Craft, Impact, Leadership)
4. Examples
5. Ready for [Next Level] When

See [templates/role-template.md](templates/role-template.md) for the complete template.

#### Keep Competencies Consistent

The three competency headers and italic descriptions are standardized:

- **Craft**: *Building excellent software through technical skill, judgment, and continuous learning.*
- **Impact**: *Taking ownership, delivering outcomes, and creating value for clients and Caldera.*
- **Leadership**: *Growing others, building shared understanding, and multiplying effectiveness.*

#### Use Observable, Behavioral Language

- Write what people DO, not what they ARE
- Focus on visible actions in a remote context
- Be specific and concrete, not vague or aspirational
- Keep role documents concise (target 50-75 lines)

#### Check Progression

When editing a role, verify it maintains clear progression:

- Compare with the level before and after
- Ensure time horizon, ownership, and scope expand appropriately
- Confirm behaviors show growth, not just different responsibilities

### 4. Commit Your Changes

Write clear, specific commit messages:

```bash
git commit -m "Clarify ownership expectations for Principal Engineer"
```

Good commit messages:
- Start with a verb (Add, Update, Fix, Clarify, Remove)
- Describe what changed and why
- Reference issues when relevant

### 5. Create a Pull Request

#### PR Title

Use a clear, descriptive title:
- "Add examples of visible work to Senior Engineer role"
- "Fix inconsistent scope language across Principal and Distinguished"
- "Update competency descriptions to match competencies.md"

#### PR Description

Include:

**What changed:**
- List specific changes made
- Reference the files modified

**Why it matters:**
- Explain how this improves the framework
- Describe who this helps and how

**Consistency check:**
- Note if changes affect multiple roles
- Confirm alignment with templates and competencies

#### Example PR Description

```markdown
## What changed
- Added 3 new examples to Senior Engineer role focusing on visible communication
- Updated "Ready for Principal When" section to clarify project ownership

## Why it matters
Several team members asked for clearer examples of what "owning delivery" looks like
in a remote context. These examples show specific, observable behaviors.

## Consistency check
- Examples align with "Working Visibly" philosophy in README
- Structure matches role-template.md
- No changes needed to other roles
```

### 6. Respond to Feedback

- Address review comments promptly
- Ask questions if feedback is unclear
- Update your PR based on discussion
- Mark conversations as resolved when addressed

## Review Process

### What Reviewers Look For

Pull requests are reviewed for:

1. **Structural consistency** - Follows the standard template
2. **Language clarity** - Specific, behavioral, observable
3. **Progression logic** - Clear growth path between levels
4. **Competency alignment** - Maps to Craft, Impact, or Leadership
5. **Philosophy alignment** - Reflects framework principles

### Approval and Merge

- At least one approval required
- Changes may be requested for consistency or clarity
- Once approved, maintainers will merge
- Expect turnaround within 2-3 business days

## Writing Guidelines

### Do

- Use active voice and behavioral language
- Focus on observable actions and artifacts
- Emphasize visibility and documentation
- Keep examples concrete and specific
- Maintain consistent structure across roles

### Don't

- Use vague aspirational language ("strive to," "should")
- Focus on internal traits over observable behaviors
- Create new section structures without discussion
- Make changes that affect multiple roles without considering alignment
- Add content that duplicates the README or competencies.md

## Questions?

- Open an issue for questions about contributing
- Tag relevant team members for context-specific questions
- Reference existing role documents for examples

## Recognition

All contributors are valued. Your contributions help create clarity and support everyone's growth at Caldera.
