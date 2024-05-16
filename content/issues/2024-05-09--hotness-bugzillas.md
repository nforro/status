---
title: "Pull from upstream disruption"
date: "2024-05-09T03:00:00+00:00"
affected:
  - Pull from upstream
resolved: true
resolvedWhen: "2024-05-16T13:15:00+00:00"
section: issue
severity: disrupted
---

There was a Fedora Infrastructure issue that caused bugzillas not being created
for new package versions appearing on release-monitoring.org. Since Packit reacts
on these bugzillas, this means that no new pull from upstream jobs were triggered.
If you are affected, you can retrigger the job by commenting `/packit pull-from-upstream`
in any dist-git pull request.
