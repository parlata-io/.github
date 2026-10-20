# .github

This repository holds the organization's default issue forms, in `.github/ISSUE_TEMPLATE/`.
GitHub offers them in every repository of the organization that has no `.github/ISSUE_TEMPLATE/` of its own.

1. The repository must stay public for GitHub to apply the forms, so it holds nothing private: no people, plans, boards, or links to private repositories.
2. Each form sets `type` to one of the organization's issue types: Task, Bug, Feature, Idea, Decision.
   A form's `name` and `description` match its issue type.
3. Each related organization's `.github` repository carries the same forms; change every copy together.
4. Changes reach `main` through a pull request, merged by squash.
