---
title: Privacy Policy — Health Sync
---

# Privacy Policy

**App:** Health Sync (Android, package `dev.arsen.hhsync`)
**Developer:** Arsen (individual developer)
**Contact:** [slowcode90@gmail.com](mailto:slowcode90@gmail.com)
**Effective date:** October 24, 2026

## 1. Summary

Health Sync is a personal, non-commercial tool. It reads your health and fitness data
from your own Huawei Health account (via HUAWEI Health Kit) and writes it into
Android Health Connect on your own phone.

- The app **only reads** data from Huawei Health. It never writes, changes or deletes
  data in Huawei Health.
- The data goes from Huawei's servers straight to your phone and into Health Connect.
  **The developer runs no server** and never receives, sees or stores your data.
- No analytics, no advertising, no tracking, no selling or sharing of data with third
  parties.

## 2. Data the app accesses

After you sign in with your HUAWEI ID and grant permission, the app may read the
following data types from HUAWEI Health Kit:

| Data type | Purpose |
|---|---|
| Steps | Written to Health Connect as step records |
| Distance | Written to Health Connect as distance records |
| Calories | Written to Health Connect as calories burned records |
| Activity records (workouts) | Written to Health Connect as exercise sessions |
| Heart rate | Written to Health Connect as heart rate records |
| Sleep (including sleep stages) | Written to Health Connect as sleep sessions |
| Blood oxygen (SpO2) | Written to Health Connect as oxygen saturation records |
| Body fat / weight | Written to Health Connect as body fat / weight records |
| Heart health (heart rate variability, resting heart rate) | Written to Health Connect as heart rate variability / resting heart rate records |

**Historical data:** on first use the app may read up to **one year** of past data of
the types above, so that your history in Health Connect is complete. After that it only
reads new data since the last sync (with a small overlap of a few hours to catch late
uploads from your wearable).

The app also handles:

- **HUAWEI ID OAuth tokens** (access and refresh tokens) — needed to call HUAWEI Health
  Kit on your behalf. The app does not see or store your HUAWEI ID password.
- **Sync state** — the time of the last successful sync.

The app does **not** collect your name, email, phone number, location, contacts, device
identifiers or any other personal data beyond what is listed above.

## 3. How the data is used

The data is used for one purpose only: **copying your health data from Huawei Health to
Health Connect on your device**. The app does not analyse, profile or show the data
for any other purpose, and it does not use it for advertising or medical decisions.

## 4. Where the data is processed and stored

- Data is downloaded over an encrypted HTTPS connection directly from HUAWEI Health Kit
  servers to your phone.
- It is converted in the phone's memory and written to **Health Connect**, which stores
  it on your device. What happens to it in Health Connect is controlled by you and by
  Health Connect's own settings and privacy policy.
- The app keeps no separate copy of your health data. Only the OAuth tokens and the sync
  time are stored, in the app's private storage, with the tokens encrypted
  (Android EncryptedSharedPreferences / Android Keystore).
- No data is sent to the developer or to any server other than HUAWEI Health Kit
  (for reading) and the HUAWEI ID service (for sign-in).
- During sign-in, HUAWEI ID returns a one-time authorization code to a static page of
  this website (hosted on GitHub Pages), which immediately hands it over to the app on
  your phone. The page stores nothing and sends the code nowhere else; the code cannot
  be used without the app's credentials and expires within minutes. No health data ever
  passes through this page.

## 5. Sharing with third parties

The app does **not** sell, rent, share, or transfer your data to any third party.
The only services the app talks to are:

- **Huawei** (HUAWEI ID and HUAWEI Health Kit) — to sign you in and read your data.
  Their processing is covered by Huawei's own privacy statements.
- **Health Connect** on your device (by Google / Android) — to store the data locally.

## 6. Data retention and deletion

- Health data passes through the app only temporarily during each sync.
- Tokens and sync state stay on your device until you sign out in the app, clear the
  app's data, or uninstall it — any of these deletes them.
- Data already written to Health Connect stays there until you delete it in the Health
  Connect settings (you can delete all data written by Health Sync at any time).

## 7. Your choices and control

- You choose which permissions to grant on the HUAWEI ID consent screen and in Health
  Connect, and you can revoke them at any time:
  - Huawei: in your HUAWEI ID account settings (authorized apps) or in the Huawei Health
    app privacy settings;
  - Health Connect: in Android Settings → Health Connect → App permissions.
- Uninstalling the app stops all access immediately.

## 8. Security

Network traffic uses HTTPS. OAuth tokens are encrypted at rest using the Android
Keystore. The app requests only read permissions and only the data types listed above.

## 9. Children

The app is not intended for children under 16 and does not knowingly process children's
data.

## 10. Not a medical device

Health Sync only copies data. It is not a medical device and does not give medical
advice, diagnosis or treatment.

## 11. Changes to this policy

If this policy changes, the updated version will be published on this page with a new
effective date.

## 12. Contact

Questions or requests about this policy: [slowcode90@gmail.com](mailto:slowcode90@gmail.com)
