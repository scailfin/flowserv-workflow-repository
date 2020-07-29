# Workflow Template Repository

This repository maintains the workflow template index file templates.json. This file contains a list of workflow templates that can be installed using the flowServ command-line interface.

The format for entries in the template index is:

```
{
    "id": "unique identifier",
    "description": "short template description",
    "url": "URL for git repository containing the template files",
    "manifest": "optional relative path to template manifest in the git repository"
}
```
