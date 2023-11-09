# nvm3

This can be reproduced with the following lines added to config.js:

```
  commitMessageLowerCase: "never",
  onboardingPrTitle: "ci: DIGIHUB-123456 configure Renovate",
  onboardingCommitMessage: "DIGIHUB-123456 configure Renovate",
  semanticCommits: "enabled" // Use semantic prefixes for commit messages and PR titles.
```
