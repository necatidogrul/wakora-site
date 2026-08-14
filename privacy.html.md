Wakora — Privacy Policy
- 

# Wakora Privacy Policy

Last updated: August 14, 2026

Wakora ("the app") is developed by Necati Doğrul. This policy explains what data the app handles and how. Short version: your data stays on your device. We do not run our own servers, we do not sell data, and we do not show ads.

## Data stored on your device only

The following data is created and stored locally on your device and is never transmitted to us:

  Alarms, labels, schedules and challenge settings
  - Wake-up streaks, statistics and snooze history
  - Wallet credit balance and its transaction history
  - App settings and preferences

Deleting the app permanently deletes this data. We cannot recover it.

## Device permissions

Wakora requests certain permissions solely to run wake-up challenges. All processing happens on-device; no photos, audio, motion or health data ever leaves your phone:

  - Camera — selfie eye-detection, QR scanning, photo-match and daylight challenges. Photos are analyzed in memory and are not uploaded.
  - Microphone & Speech Recognition — the Voice Vow challenge. Audio is processed on-device via Apple's speech framework.
  - Motion & Fitness — shake, step, squat, push-up and jumping challenges.
  - Health (read-only heart rate) — the Apple Watch wake-verification challenge. We never write to or export HealthKit data.
  - Notifications — ringing your alarms.

## Face data

Wakora does **not collect, store, transmit, share or sell face data**. Face data never leaves your device and is never retained.

  - **When it happens.** Only inside the optional "Selfie" wake-up challenge, and only after you tap the shutter yourself. If you do not enable that challenge, no face data is ever processed.
  - **What is processed.** The still photo you take with the front camera is passed to Apple's on-device Vision framework (`VNDetectFaceLandmarksRequest`). Vision returns the positions of the eye landmarks in that single image. Wakora uses those positions for one purpose only: to compute a yes/no answer to "are the eyes open?" and dismiss the alarm.
  - **What is *not* done.** Wakora does not create a faceprint or face template, does not identify or recognise anyone, does not match faces against any database or against previously taken photos, does not infer age, gender, emotion, health or any other attribute, and does not use Face ID, ARKit face tracking or TrueDepth depth data.
  - **Storage.** The photo and the landmark positions exist only in the device's memory (RAM) while the challenge screen is open. They are never written to disk, never saved to your Photos library, never placed in iCloud and never uploaded to us or to anyone else. Wakora has no server that could receive them.
  - **Retention.** Zero retention. The photo and landmark positions are discarded the moment the challenge ends or you leave the screen — typically within seconds. Nothing persists, so there is nothing to delete or export. Deleting the app removes all remaining local app data.
  - **Sharing.** Face data is not shared with any third party, service provider, analytics provider, advertiser or affiliate. The app contains no advertising or analytics SDKs.

Separately, the optional "Photo Match" challenge lets you save one reference photo of your own choosing (for example, a bathroom mirror or a cereal box). That photo is stored only in the app's private container on your device and is compared with a general image-similarity feature print — no face detection, no face recognition and no face data is used in that challenge. Deleting the app deletes the reference photo.

## Purchases

Subscriptions and wallet credit top-ups are processed by Apple through the App Store. We use [RevenueCat](https://www.revenuecat.com/privacy) to validate purchases and manage subscription status. RevenueCat receives an anonymous app-generated identifier and purchase receipts — never your name, email or Apple ID. Wallet credits are prepaid in-app credits: they never expire and are only spent when you explicitly choose to snooze. Wallet credits have no cash value outside the app and cannot be withdrawn or transferred.

## Analytics and tracking

The app contains no advertising SDKs and no third-party analytics or tracking SDKs. We do not track you across apps or websites.

## Children

Wakora is not directed at children under 13 and does not knowingly collect data from them.

## Changes

If this policy changes, the updated version will be posted at this address with a new date.

## Contact

Questions? Email [necatidogrul7@gmail.com](mailto:necatidogrul7@gmail.com).
