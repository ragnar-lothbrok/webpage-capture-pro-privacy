# Privacy Policy — Page Capture Pro

**Effective date:** October 30, 2026

Page Capture Pro is a Chrome extension that saves web pages as screenshots, MHTML/HTML files and ZIP bundles, and builds side-by-side comparison reports. This policy explains what the extension does with data.

## Summary

Page Capture Pro does **not** collect, store, transmit, sell or share any personal data. Everything happens locally in your browser, and every file it creates is saved to your own computer.

## What the extension accesses

To do its job, the extension reads the page you ask it to capture:

- **Page content and screenshots** of the current tab, only when you click a capture button.
- **Pages you enter for Compare or Go to URL**, which the extension opens in your tab so it can capture them.
- **Page assets** (images, stylesheets, fonts) when you choose a ZIP export with assets. These are downloaded from the page's own servers, just as your browser loads them when you view the page.

This content is processed in memory and written straight to your Downloads folder. None of it is sent to the developer or any third party.

## What the extension does not do

- No accounts, sign-ins or user profiles.
- No analytics, tracking, telemetry or advertising.
- No remote servers. The extension has no backend and makes no network requests other than fetching the page assets described above.
- No browsing history collection. The extension does not run in the background or on pages you haven't asked it to capture.
- No data stored by the extension. It keeps no settings, history or captures in browser storage.

## Permissions

| Permission | Why it is needed |
|---|---|
| `activeTab` | Access the tab you are on, only after you open the extension. |
| `tabs` | Read the current tab's URL and title for file names, and load the URLs you enter for Compare and Go to URL. |
| `scripting` | Run capture code in the page: scroll for full-page screenshots, hide cookie banners and overlays, collect assets. |
| `pageCapture` | Save the page as an MHTML file. |
| `downloads` | Save screenshots, MHTML/HTML files, ZIP bundles and reports to your computer. |
| Optional site access (`<all_urls>`) | Requested only when you use Compare or Go to URL, so the extension can capture pages on other sites. You can decline it or remove it at any time in `chrome://extensions`. |

## Your files

Captured files exist only where you save them. The extension cannot see or delete them afterwards. You control them completely.

## Children's privacy

The extension collects no data from anyone, including children under 13.

## Changes to this policy

If the extension's data practices ever change, this policy will be updated and the effective date above will change. Material changes will be noted in the extension's release notes.

## Contact

Questions about this policy can be raised at https://github.com/ragnar-lothbrok/webpage-capture-pro/issues.
