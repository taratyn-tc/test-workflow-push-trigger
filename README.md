# test-workflow-push-trigger
Does a push event fire when I merge a PR?

This sentence was added in a branch and merged in a PR! See #1.

The Workflow is fired on the branch:

![Workflow fires on branch.](images/on-branch-workflow-is-fired.png)

And it fired for the merge commit:

![images/on-merge-workflow-is-fired.png](images/on-merge-workflow-is-fired.png)

And it fires when you commit right on `main`:

![images/on-commit-on-main-workflow-is-fired.png](images/on-commit-on-main-workflow-is-fired.png)
