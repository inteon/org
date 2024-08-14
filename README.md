# cert-manager GitHub Organization

This repository contains the metadata configuration for the cert-manager GitHub Organizations.
The data here is consumed by the [peribolos tool](https://github.com/kubernetes-sigs/prow/tree/ea10bd8144c3d988528011af024abe47ea8dabb2/cmd/peribolos) to manage GitHub organizations, teams and repos.

## Contributing

This repository is mostly managed by the cert-manager admins. If you need to request access to a team, please open an issue in the community repository: https://github.com/cert-manager/community.

Instructions for cert-manager admins:
1. create a PR with the proposed changes
2. reviewers can dry-run the peribolos tool to see the changes that will be made
3. once the PR is approved and merged, an admin has to run the peribolos tool again to apply the changes

See `./admin/README.md` for instructions on how to manually run the peribolos tool (only possible for cert-manager admins).
