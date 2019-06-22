# AppDaemon developers

A template to use as a reference is [ad-hacs](https://github.com/ludeeus/ad-hacs)

## Requirements

For a AppDaemon app repository to be valid these are the requirements:

### Repository structure

- There is only one app (one directory under `ROOT_OF_THE_REPO/apps/`) pr. repository (if you have more, only the first one will be managed.)
- The app (all the python files for it) are located under `ROOT_OF_THE_REPO/apps/APP_NAME/`
- The app and all the python files for it are located under `ROOT_OF_THE_REPO/apps/APP_NAME/`

#### OK example:

```text
apps/awesome/awesome.py
info.md
README.md
```

#### Not OK example (1):

```text
awesome/awesome.py
info.md
README.md
```

#### Not OK example (2):

```text
awesome.py
info.md
README.md
```

### GitHub releases (optional)

#### If there are releases

When installing/upgrading it will scan the content in the latest release.

#### If there are no releases

It will scan files in the branch marked as default.

<!-- Disable sidebar -->
<script>document.getElementsByClassName("bs-sidebar").item(0).style.display = "none";</script>
<!-- Disable sidebar -->