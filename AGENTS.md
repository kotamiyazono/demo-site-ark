# Agent Instructions for ARK

## Pull Request Workflow

### CRITICAL: Draft to Ready for Review Transition

When you complete the task implementation:

1. **REQUIRED ACTION**: You MUST mark the PR as "Ready for Review" by running:
   ```bash
   gh pr ready
   ```
   
2. This command is **MANDATORY** - without it, the task status will not progress and the human reviewer cannot see your work.

3. Run this command when:
   - All code changes are committed and pushed
   - The implementation satisfies the task requirements
   - Tests pass (if applicable)

### Important Notes
- PRs are created as draft by default
- Do NOT merge PRs - human approval is always required
- The `gh pr ready` command must be executed in the PR branch context
