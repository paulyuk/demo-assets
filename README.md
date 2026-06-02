# demo-assets

Public hosting for animated GIFs and screenshots used in blog announcements
and PR descriptions (where the source repo is private and inline rendering
needs a public URL).

| Folder | Demo | Source PR |
|---|---|---|
| [`functions-cli-v5/`](functions-cli-v5/) | Azure Functions CLI v5 (Preview) 30s demo | https://github.com/coreai-microsoft/azure-functions-leads/pull/36 |

To embed in a PR description, use the SHA-pinned `raw.githubusercontent.com` URL
(re-pin whenever the GIF bytes change so caches don't go stale):

```
![alt](https://raw.githubusercontent.com/paulyuk/demo-assets/<sha>/<path>.gif)
```
