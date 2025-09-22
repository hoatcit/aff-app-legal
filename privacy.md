# Privacy Policy — Aff Fashions Poster

**Effective date:** 2025-09-22

This Privacy Policy explains how **Aff Fashions Poster** (“App”) handles information.

## 1. What We Handle
- **TikTok OAuth tokens** (access/refresh) to post on your behalf.
- **Google Sheets metadata** (read/write specific cells for status/captions).
- **Local file paths** to your videos; processing is done on your device.
- **Basic logs** (timestamps, success/error messages) for troubleshooting.

## 2. How We Use Information
- Authenticate with TikTok and Google.
- Prepare and submit videos via TikTok’s Content Posting API.
- Update Google Sheets (“Đã đăng”) after successful posting.
- Show creator info (privacy options) for Direct Post compliance.

## 3. Storage & Security
- Tokens and configs are stored **locally on your computer** (e.g., `tokens.json`, `config.json`, `logs/`).
- No cloud storage by default. You control the machine and files.
- If you host the App elsewhere, ensure appropriate security and access controls.

## 4. Sharing
We **do not sell** or share information with third parties. Data flows only to:
- TikTok (to perform posting)  
- Google (to read/write your sheet)  
as required by the features you use.

## 5. Cookies/Tracking
The local UI does not use analytics cookies. If you deploy it on the web, your hosting environment may introduce server logs.

## 6. Data Retention
- Tokens/config persist until you delete them or revoke access on TikTok/Google.
- Logs are rotated (e.g., 5×5MB). You may delete them at any time.

## 7. Your Choices
- Revoke TikTok/Google access at any time via their account settings.
- Delete local files (`tokens.json`, `logs/`) to remove stored data.
- Adjust captions, schedules, and AIGC flags via the App UI/config.

## 8. Children
The App is not directed to children under 13.

## 9. Changes
We may update this Policy. We will update the “Effective date” above.

## 10. Contact
Questions? Email: **nguyenconghieuaff@gmail.com**
