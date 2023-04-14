---
date: 2023-04-14T15:52:13Z
title: "chainctl iam groups set-gcp"
slug: chainctl_iam_groups_set-gcp
url: /chainguard/chainctl/chainctl-docs/chainctl_iam_groups_set-gcp/
draft: false
images: []
type: "article"
toc: true
---
## chainctl iam groups set-gcp

Set the GCP project association for this IAM Group.

```
chainctl iam groups set-gcp [GROUP_NAME | GROUP_ID] [--project-id PROJECT_ID] [--project-number PROJECT_NUMBER] [--output |json|table] [flags]
```

### Options

```
  -d, --description string      The description of the association.
  -h, --help                    help for set-gcp
  -n, --name string             The name of the association. (default: the group name)
      --project-id string       The GCP project ID.
      --project-number string   The GCP project number.
```

### Options inherited from parent commands

```
      --api string                   The url of the Chainguard platform API. (default "http://api.api-system.svc")
      --audience string              The Chainguard token audience to request. (default "http://api.api-system.svc")
      --config string                A specific chainctl config file.
      --console string               The url of the Chainguard platform Console. (default "http://console-ui.api-system.svc")
      --issuer string                The url of the Chainguard STS endpoint. (default "http://issuer.oidc-system.svc")
  -o, --output string                Output format. One of: ["", "table", "tree", "json", "id", "wide"]
      --timestamp-authority string   The url of the Chainguard Timestamp Authority endpoint. (default "http://tsa.timestamp-authority.svc")
  -v, --v int                        Set the log verbosity level.
```

### SEE ALSO

* [chainctl iam groups](/chainguard/chainctl/chainctl-docs/chainctl_iam_groups/)	 - IAM Group resource interactions.
