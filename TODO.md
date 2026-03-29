# TODO: PR publish path (heavygee fork)

- [ ] Open PR from forked branch when ready

Command:

```bash
gh pr create --repo heavygee/ralph-wiggum-cursor --base main --head fix/no-op-loop-model-progress-guard --title "Fix no-op loop detection in ralph common loop" --body "Add model validation and guard against consecutive no-progress iterations to prevent infinite no-op loops."
```

- [ ] If needed, verify branch and remote:
  - `git -C /home/heavygee/coding/ralph-wiggum-cursor status`
  - `git -C /home/heavygee/coding/ralph-wiggum-cursor remote -v`
- [ ] Commit present on fork: `34b6944`.
