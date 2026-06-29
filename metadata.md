# Star and Silk App Store Metadata

Use this file as the paste-ready handoff for App Store Connect.

## Current Status

- App Store Connect app record: created
- App Store Connect app ID: `6778802797`
- Current internal TestFlight build to test: `1.0 (10)`
- Internal TestFlight group: `Internal QA`
- Current build status: build `1.0 (10)` is the next candidate pending App Store Connect upload/processing; build `1.0 (9)` is already in TestFlight but is superseded because it does not include the shared header clipping fix.
- Build note: `1.0 (3)` supersedes `1.0 (2)` because it includes the full-screen launch-screen fix for modern iPhones.
- Build note: `1.0 (4)` supersedes `1.0 (3)` because it fixes first-run onboarding clarity, birth year entry, and birth city selection.
- Build note: `1.0 (5)` supersedes `1.0 (4)` because it includes the birth-time confidence reliability fix and TestFlight readiness copy cleanup.
- Build note: `1.0 (6)` supersedes `1.0 (5)` because it fixes real-device visual cleanup issues found in TestFlight screenshots: status bar overlap, premium CTA contrast, and softer chart/Sky technical labels.
- Build note: `1.0 (8)` supersedes `1.0 (6)` because it includes the final launch-polish UI pass, readable My Chart wheel, improved bottom spacing, composed App Store screenshot support, and a free-v1 launch path with paid Premium hidden.
- Build note: `1.0 (9)` supersedes `1.0 (8)` because it fixes the excessive blank scrollable space at the bottom of main tabs.
- Build note: `1.0 (10)` supersedes `1.0 (9)` because it includes the shared header clipping fix plus DEBUG-only launch hardening and UI smoke automation.
- Final public submission still needs real-device TestFlight smoke approval and completed App Store Connect review fields.

## Identity

- App Name: `Star and Silk`
- Bundle ID: `com.phillip.starandsilk`
- SKU recommendation: `starandsilk-ios-001`
- Primary category recommendation: `Lifestyle`
- Secondary category recommendation: leave blank for launch
- Age rating expectation: complete Apple's questionnaire honestly; no mature content is expected from the current app

## URLs

Use these public GitHub Pages URLs for v1 until `starandsilk.app` DNS and HTTPS are connected to the static support/privacy site. Support email is `support@starandsilk.app`.

- Support URL: `https://pmdowd6.github.io/starandsilk-app-pages/support.html`
- Privacy Policy URL: `https://pmdowd6.github.io/starandsilk-app-pages/privacy.html`
- Marketing URL, optional: `https://pmdowd6.github.io/starandsilk-app-pages/`
- Terms page, optional: `https://pmdowd6.github.io/starandsilk-app-pages/terms.html`
- License agreement recommendation: use Apple's Standard EULA for launch

## App Store Text

### Subtitle

Astrology from your chart

Character count: 25 of 30.

### Promotional Text

Private daily clarity from your real chart, with chart data saved on-device.

Character count: 72 of 170.

### Keywords

daily astrology,birth chart,natal chart,transits,horoscope,moon phase,retrograde,private astrology

Character count: 98 of 100.

### Description

Star and Silk is a private astrology app for people who want a clearer read on their day.

Built from your real birth chart, Star and Silk combines natal chart insight with daily transits to show what is shaping your mood, timing, and energy right now. Your chart data and readings are saved on your iPhone, while optional location lookup uses Apple services.

Use Star and Silk to:

- read the tone of your day through your chart
- see what to lean into and what to avoid
- understand the strongest transit drivers behind the day
- check moon phase and retrogrades
- revisit recent readings and spot recurring themes

Features:

- full natal chart with planets, houses, ASC, and MC
- daily reading with Vibe, Do, Avoid, and Focus
- transit ranking and planetary context
- 7-day forecast
- local notifications
- private on-device storage
- on-device astrology calculations

All current reading, chart, Sky, forecast, and history features are included in the launch version. There are no in-app purchases in v1.

## App Review Notes

Star and Silk is a private astrology app whose core chart and daily readings are generated on-device from the user's birth details. Location is optional and only used after the user taps Use Current Location; typed city lookup may use Apple's geocoding service. The launch version has no account, no in-app purchases, no ads, no third-party analytics SDK, and no developer-run external profile server.

## App Privacy Notes

Recommended App Privacy answers for the current launch build:

- Data collected: `No`
- Data used to track you: `No`

Reasoning:

- Birth profile, chart data, readings, settings, and history are stored locally on-device.
- The app does not use third-party analytics SDKs, ad SDKs, account login, or a backend profile service.
- Optional location access is used only after the user taps Use Current Location to fill coordinates during setup and is not sent to a developer-run server.
- Typed city lookup may use Apple's geocoding service to return coordinates.
- The launch version does not sell subscriptions or in-app purchases.

Recheck these answers before submission if analytics, crash reporting, account sync, or server features are added.
