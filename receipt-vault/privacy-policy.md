# Privacy Policy – Receipt Vault

Last updated: 2026-10-05

> **Before publishing:** replace `[Developer name]` and `[contact email]`, host this page at a public URL and enter that
> URL in the Play Console and in `privacy.policyUrl` (see `docs/RELEASE.md`). Have it checked against the final SDK
> versions and your legal situation; it describes how the app is built today, it is not legal advice.

**Receipt Vault** ("the app") is published by [Developer name] ("we"). You can reach us at [contact email].

## The short version
- The app has **no account and no server of ours**. Your receipts are read and stored **on your phone**.
- We cannot see your receipts, prices, store names, notes or serial numbers, and we never send them to analytics or crash reports.
- Optional features send data **only to places you choose**: your own Google Drive (backup), or an app you pick in the Android share sheet (claim pack PDF, backup ZIP).
- The app shows ads. Advertising and analytics SDKs from Google collect limited technical data, and only after you agree where the law requires it.

## What the app stores on your device
- Receipt photos and PDFs you scan, import or share into the app.
- The text the app reads from them (recognised on your device, for search) and the details you confirm: item name, store, category, purchase date, price and currency, return and warranty dates, serial number and notes.
- Settings: country, currency, reminder time, and whether the optional app lock and Drive backup are on.

All of it stays in the app's private storage until you delete the item, use "Delete", or uninstall the app. Android's own
backup (Auto Backup) may copy the app's database and settings, but not the receipt files, to your Google account if you have
device backup turned on; that is controlled by your phone's settings.

## Features that send data
**Google Drive backup (optional, off by default).** If you turn it on, the app signs you in with Google and uploads a copy of
the database and the receipt files to a private, hidden "app data" folder in **your own** Google Drive. The app cannot see your
other Drive files. We do not receive this data. You can turn the backup off in Settings and delete the backup data in your
Google account's settings (Manage apps and storage). Restoring downloads it back to your phone.

**Exports.** The claim pack PDF and the backup ZIP are created on your phone. They leave the app only when you share them with the app you pick.

**Reminders** are created on your phone from the dates you entered. Notifications are marked private on the lock screen.

**Document scanning and text recognition.** The camera scanner is a Google Play services component and the text recognition runs
on your device. The scanner component may be downloaded by Google Play services the first time you use it. Receipt images are not sent to us.

## Third-party services
| Service | Used for | Data involved | When |
|---|---|---|---|
| Google AdMob (Google Mobile Ads) | Rewarded ad (opt-in, before exports) and one ad in the list | Advertising ID, IP address, device and app information, ad interactions | After consent where required |
| Google User Messaging Platform | Asking for your consent | Your consent choice | At first start (and via Settings → Privacy options) |
| Firebase Analytics | Counting feature use | Event names with coarse values (for example "scan started", source: camera/photo/PDF), device and app information | After consent |
| Firebase Crashlytics | Fixing crashes | Crash logs, device and app information | After consent |
| Firebase Remote Config | Switching ad features on or off | App and device identifiers needed to fetch settings | After consent |
| Google Play services, Google Sign-In / Credential Manager, Google Drive | Backup (only if you turn it on) | Your Google account and the backup files | Only when you use backup |
| Google Play In-App Review | Asking you for a rating | Handled by Google Play | Rarely, once |

We never put receipt content into analytics events or crash reports. Google's own privacy policies apply to their services:
https://policies.google.com/privacy

## Your choices
- **Ads and analytics:** you can change your consent at any time in Settings → Privacy options (shown where the law requires a choice). On Android you can also reset your advertising ID in the system settings.
- **Notifications:** turn them off in Settings → Notification settings.
- **Backup:** turn it off in Settings; delete the Drive data in your Google account.
- **Delete everything:** delete items in the app, or clear the app's data / uninstall it.
- **Access, correction, deletion, objection (for example under the GDPR):** because we hold no data about you, there is nothing for us to access or erase. Requests about data held by Google (advertising, analytics, crash reports, Drive) go to Google through its privacy tools. You can still write to [contact email].

## Children
The app is not meant for children under 18 and the Play Store listing is set to adults only.

## Security
The app uses Android's standard protections: private app storage, HTTPS for every network connection, and an optional
fingerprint or face lock for opening the app. No system can promise absolute security.

## International transfers
Data handled by Google services may be processed in other countries under Google's terms and safeguards.

## Changes
If this policy changes, the date at the top changes and, for significant changes, the app tells you.

## Contact
[Developer name], [contact email]
