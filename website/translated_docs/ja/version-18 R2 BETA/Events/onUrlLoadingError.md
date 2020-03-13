---
id: version-18R2_BETA-onUrlLoadingError
title: On URL Loading Error
original_id: onUrlLoadingError
---

| Code | Can be called by                            | Definition                                 |
| ---- | ------------------------------------------- | ------------------------------------------ |
| 50   | [Web Area](FormObjects/webArea_overview.md) | An error occurred when the URL was loading |


## 説明

This event is generated when an error is detected during the loading of a URL.

You can call the `WA GET LAST URL ERROR` command in order to get information about the error.

### See also

[`On Open External Link`](onOpenExternalLink.md)