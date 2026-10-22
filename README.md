<div align="center">

# Zlet Converter

### Documents in. Clean Markdown out. Locally.

A privacy-first Windows desktop app for turning documents into usable Markdown.

<br>

![Windows](https://img.shields.io/badge/Windows-x64-2f81f7?style=flat-square)
![Local first](https://img.shields.io/badge/processing-local--first-238636?style=flat-square)
![License](https://img.shields.io/badge/license-Free%20Personal%20Use-238636?style=flat-square)
![Beta](https://img.shields.io/badge/v0.1.0--beta.1-in_preparation-d29922?style=flat-square)

<br>

[**Download latest release**](https://github.com/zlet-labs/zlet-converter-releases/releases/latest) · [All releases](https://github.com/zlet-labs/zlet-converter-releases/releases)

</div>

---

## Why Zlet Converter

Most document converters can extract text. Zlet Converter is being built around a stricter goal: **produce Markdown that remains useful after conversion**.

| | |
| --- | --- |
| 🔒 **Local-first** | Supported conversion routes process documents on your machine. |
| 🧱 **Structure matters** | Headings, lists, tables, links, and reading order matter more than dumping text into a file. |
| 🧭 **Format-aware** | Different document types can use different conversion routes when that improves results. |
| 📚 **Batch-friendly** | Convert multiple documents and export results without repetitive manual work. |
| ⚠️ **Honest diagnostics** | Unsupported or degraded capabilities should be explicit instead of looking like success. |
| 🆓 **Free Beta.1** | Free for personal, non-commercial use only. A separate Pro edition is planned for commercial use; pricing and release date are not yet set. |

## Public Beta

The first Public Beta, **v0.1.0-beta.1**, is in preparation.

**Starting with Beta.1, Free is licensed for personal, non-commercial use only.** Redistribution, repackaging, modifications and reuse of Zlet Labs-owned modules/source require written permission. No activation or account is needed. Read the [Free Personal License](LICENSE_FREE_BETA1.txt) before installing or using Beta.1. This limitation does not revoke rights to historical MIT-licensed releases or independently licensed third-party code.

The core workflow is deliberately simple:

> **Add documents → Convert → Check quality → Review → Open / Export**

Conversion status and **Basic Quality Check** are separate signals. A completed conversion can still require review, so the Beta keeps quality visible without pretending every successful conversion is automatically a good result.

Earlier builds remain available as historical **PRE-ALPHA** releases.

## Downloads

Official builds are published in [**GitHub Releases**](https://github.com/zlet-labs/zlet-converter-releases/releases).

Depending on the release, downloads may include:

- Windows x64 installer
- Portable ZIP
- SHA-256 checksums
- Release notes and known limitations

> **Early-build note:** installers may be unsigned, so Windows can display an Unknown publisher or SmartScreen warning. Check the notes for the specific release before installing.

## Product scope

Zlet Converter is intentionally narrow:

1. **Documents → high-quality Markdown**
2. **Legacy Office → modern Office formats**, where an appropriate local route is available

No mandatory account. No mandatory cloud service. No mandatory LLM API.

## Privacy & development

This repository is the **public distribution home** for Zlet Converter. Product development, source code, tests, and engineering infrastructure are maintained separately.

The product is designed around local processing, reproducible behavior, explicit diagnostics, and preservation of useful document structure.

---

<div align="center">

Built by **[Zlet Labs](https://github.com/zlet-labs)**

<sub>Local-first software. Evidence over claims.</sub>

</div>
