Transcend's fork of https://github.com/andydunstall/piko, just used to create extra releases

For Transcend-folk:
- it's probs best to reset hard to the fork head before new changes
- bump the version in operations/helm/piko/Chart.yaml to the version you want
- builds are triggered when you open a PR or push to main
- releases are triggered on pushes to git tags starting with `v`. Run something like `git tag v0.8.2 && git push origin v0.8.2` making sure to update the version in both places

We've slimmed down the release workflow to only release the linux binaries