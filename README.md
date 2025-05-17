# git-hooks
General purpose git hooks

## TL;DR

```
git clone https://github.com/quiram/git-hooks.git
cd git-hooks
./install-git-hooks

# If you have existing repos at <development_folder> and want to apply the hooks to them
./apply-git-hooks <development_folder> 
```

## Hooks
`prepare-commit-msg`
If the branch name matches a JIRA ticket pattern (e.g. `JIRA-123` or `feature/JIRA-456` or `bug/amarinpe/JIRA-789`), the jira ticket will be appended to the commit message.
