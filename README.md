# KTH-DevOps-AutoLabeller
Github action to autmatically label pull requests according to the specs in the DevOps course (DD2482)

The action works by matching regular expressions in the title or body of the pull request and then assigning a label based on the matches.

The labels and regular expressions can be found in ```.github/labeler.yml```.

## Currently supported labels

- proposal
- final_submission
- presentation
- demo
- course_automation
- essay
- tutorial
- feedback
- contribution_to_opensource
