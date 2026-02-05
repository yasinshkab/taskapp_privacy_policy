---
layout: default
title: Privacy Policy
---

# Privacy Policy

Last updated: Feb 5, 2026

This Privacy Policy explains how Task Control ("the App") collects, uses, and shares information when you use the App. By using the App you agree to the collection and use of information in accordance with this policy.

## Data We Collect
- Microphone audio: The App uses speech-to-text to transcribe voice input. Audio is processed on-device when possible and/or sent to the speech recognition service provided by the `speech_to_text` plugin. No audio is uploaded to our servers by default except when you explicitly use features that sync to Firebase.
- Firebase account information: If you sign in, we store basic account identifiers and profile information required for authentication.
- App data: Tasks, notes, and widget configuration are stored locally. If you enable cloud sync, task data is stored in your Firebase Realtime Database.
- Device identifiers: Basic device information required for app functionality (OS version, device model) and crash/diagnostic data if you enable diagnostics.

## How We Use Data
- Provide core app functionality (task creation, sync, widgets, notifications).
- Synchronize user data across devices when you opt into Firebase sync.
- Send push notifications and scheduled reminders.

## Third-Party Services
We use Firebase for authentication and realtime database storage. We may use third-party plugins for notifications, scheduling, and speech recognition. These services are governed by their own privacy policies.

## Ads and Analytics
This app does not serve ads. If analytics or advertising libraries are added in future releases, we will disclose them and update this policy.

## Permissions
- Microphone: required for voice input and speech-to-text features.
- Exact alarms / background services: used to schedule reminders and update home screen widgets.

## Sharing and Disclosure
We do not sell your personal information. We may disclose data to comply with legal obligations or to protect rights and safety.

## Data Safety and User Controls
- You can opt out of cloud sync by disabling account sign-in.
- To delete your data, disable cloud sync and remove account data within the app. If you have enabled cloud sync, you may need to remove cloud-stored data from the Firebase project (this is not automated by the app).

---

Template notes: Update any details about server-side processing if you introduce cloud services beyond Firebase.
