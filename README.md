# node-commit-hooks

A minimal example of enforcing commit message conventions in a Node project, using [husky](https://github.com/typicode/husky) git hooks and [commitlint](https://commitlint.js.org/) with the conventional commits config.

## Setup

```bash
npm install
```

Husky installs the git hook from `.huskyrc`, and commitlint checks each commit message against the rules in `.commitlintrc.js` (`@commitlint/config-conventional`). A message such as `feat: add a thing` passes; `added a thing` is rejected.

## Status

A small experiment from 2019 (husky 2, commitlint 7). Husky's setup has changed a lot since, so treat it as a historical example.
