---
"wry": patch:bug
---

On Linux, `WebView::bounds` returns the position and size of a webview in a `gtk::Fixed`, instead of `(0, 0)` and its last allocation.
