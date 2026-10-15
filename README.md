# FreeXmlToolkit Scoop bucket

[Scoop](https://scoop.sh/) bucket for [FreeXmlToolkit](https://github.com/karlkauc/FreeXmlToolkit) – a free XML editor
and toolkit with XSD/Schematron validation, XSLT/XQuery, schema documentation and PDF generation.

## Install

```powershell
scoop bucket add karlkauc https://github.com/karlkauc/scoop-bucket
scoop install freexmltoolkit
```

FreeXmlToolkit then appears in the Start menu under *Scoop Apps*.

## Update

```powershell
scoop update freexmltoolkit
```

The app tells you when a new version is available and shows this command; it does not update itself
when installed through Scoop.

## Uninstall

```powershell
scoop uninstall freexmltoolkit
```

Settings in `%USERPROFILE%\.freeXmlToolkit` are kept; delete the folder to remove them as well.

## About this bucket

The manifest `bucket/freexmltoolkit.json` is updated automatically for every
[FreeXmlToolkit release](https://github.com/karlkauc/FreeXmlToolkit/releases) (portable Windows x64 package,
SHA-256 from the release's `SHA256SUMS.txt`). Please report problems in the
[FreeXmlToolkit issue tracker](https://github.com/karlkauc/FreeXmlToolkit/issues).
