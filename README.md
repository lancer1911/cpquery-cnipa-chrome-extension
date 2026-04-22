# Patent Information Query Enhancement Tool
> Chrome Extension · For the [CNIPA Patent Search and Analysis System](https://cpquery.cponline.cnipa.gov.cn/)
>
> **Current Version: v4.0**

---

## Overview

<table>
  <thead>
    <tr>
      <th>Feature</th>
      <th>Description</th>
      <th>Screenshot</th>
      <th>Access</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>📄 Images to PDF</td>
      <td>Merges multiple images into a single PDF on the case details page</td>
      <td><img src="images/screenshot-6.png" width="300"/></td>
      <td>Available to All Users</td>
    </tr>
    <tr>
      <td>📥 Direct PDF Download</td>
      <td>Adds a download button on the PDF viewer page. The downloaded file name includes the application number and title</td>
      <td><img src="images/screenshot-5.png" width="300"/></td>
      <td>Available to All Users</td>
    </tr>
    <tr>
      <td>📊 Oral Hearing Notice Export</td>
      <td>Automatically turns pages and exports Excel data on the oral hearing notice list page</td>
      <td><img src="images/screenshot-3.png" width="300"/></td>
      <td><strong>PRO</strong></td>
    </tr>
    <tr>
      <td>📋 Reexamination / Invalidation Decision Export</td>
      <td>Automatically downloads PDFs and exports Excel data on the invalidation decision list page</td>
      <td><img src="images/screenshot-2.png" width="300"/></td>
      <td><strong>PRO</strong></td>
    </tr>
    <tr>
      <td>📡 Litigation / Invalidation Alert</td>
      <td>Automatically identifies potential litigation or invalidation risks for target patents by monitoring payment records for invalidation requests, patent register copies, and patent evaluation reports</td>
      <td><img src="images/screenshot-1.png" width="300"/></td>
      <td><strong>PRO</strong></td>
    </tr>
  </tbody>
</table>

## Installation

1. Go to the [Releases](../../releases) page and download the latest `.zip` package.
2. Extract the package to any local folder.
3. Open Chrome and enter `chrome://extensions/` in the address bar.
4. Turn on **Developer mode** in the upper-right corner.
5. Click **Load unpacked** and select the extracted folder.
6. Once the extension icon appears in the toolbar, the installation is complete.

---

## Unlocking PRO Features

Click the extension icon in the toolbar and locate the **★ PRO** section at the bottom of the popup settings panel:

1. Enter your authorized email address in the **Email** field.
2. Enter the corresponding authorization code in the **UUID** field.
3. Click **Unlock**. Once verification succeeds, the PRO features will be activated immediately.

> The authorization code is valid for **6 weeks**, and the unlocked status remains valid for **6 months**. After expiration, a new authorization code must be entered to unlock the PRO features again.

The PRO features of this project are provided only to internal test users and are not available to external users.

---

## Instructions for Use

**Note: when using the extension for the first time, the browser may block pop-ups. Please handle it as follows:**

**Method 1:** Click the browser prompt and choose **Always allow pop-ups and redirects from cpquery.cponline.cnipa.gov.cn**.

<img src="images/guide_popup_warning.png" width="350"/>

**Method 2:** Click the icon on the left side of the address bar, then manually change **Pop-ups and redirects** to **Allow**. Also set **Automatic downloads** to **Allow**.

<img src="images/guide_site_permission.png" width="350"/>

> After changing these permission settings, please **refresh the page** before using the export features.

---

## Notes

- This extension is for personal learning purposes only. The code has been obfuscated. Please do not attempt to crack or reverse engineer it.
- PRO features are not available to external users.
- This extension runs only under the `cpquery.cponline.cnipa.gov.cn` domain and does not read or upload any user data.
- During batch processing, the extension automatically inserts random intervals between records. Please do not manually operate the page during the process.
- Exported data is for reference only. Please refer to the information displayed in the official system as the final authority.
