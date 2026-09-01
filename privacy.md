---
title: Privacy Policy
---

# BenkyoReader — Privacy Policy

**Effective 1 September 2026.** Questions or requests about your data:
open an issue at
<https://github.com/tarekgabarin/benkyoreader-legal/issues>.

BenkyoReader is a Japanese reading tool. You photograph text, it reads the
text back to you with dictionary definitions, and you save words you want to
remember. This policy describes exactly what leaves your device, when, and to
whom. It was written from the app's source code, not from a template.

## The short version

- **Signed out, nothing about you reaches our servers.** The app does not
  contact our backend at all until you sign in.
- **We never receive your email address or your name.** Sign in with Apple is
  requested with no name or email scope, so Apple does not send them to us.
- **We show no ads, use no analytics, and do not track you** across apps or
  websites.
- **Photographed text is sent to Google** to be recognised. This is the one
  thing in this policy most people will not expect, so it has its own section.
- **You can delete everything from inside the app**, and download it first.

## What we collect, and only if you sign in

Signing in is optional. The app is fully usable signed out, and everything
you save stays on your device.

When you sign in with Apple, we receive and store:

- **An anonymous Apple identifier.** Apple gives us an opaque subject id for
  your account. We do not receive your email address or your name.
- **The words and decks you save**, so they can appear on your other devices:
  the written form, its reading, the dictionary definition shown, the example
  sentence captured with it, your deck names, which words belong to which
  deck, and the times each was changed or removed.

The example sentence is a short piece of text from something you
photographed, so treat it as you would any note you write.

We do not collect your location, contacts, health data, photos library,
payment information, or any advertising identifier.

## Text and images sent to Google

BenkyoReader uses two Google services. Neither receives your account
identifier, your name, or your email, and we do not send them anything that
identifies you. Google receives your device's IP address as part of any
internet request, and Google's own privacy policy governs what it does with
what it receives.

**Text recognition (automatic).** When you scan a page of horizontal text or
a document page, the photograph is sent to Google Lens
(`lensfrontend-pa.googleapis.com`) to be converted into text. Vertical
Japanese text — the usual case for manga — is recognised entirely on your
device and is never uploaded. We do not store your photographs on our
servers; the image is used to obtain the text and is not retained by us.

**Pronunciation (only if you choose it).** If you select the Google voice in
Audio settings, the word or sentence you asked to hear is sent to Google's
text-to-speech service (`translate.google.com`) to produce the audio. The
default is your device's built-in voice, which sends nothing anywhere. The
returned audio is cached on your device so the same word is not requested
twice.

## Where your data is kept, and for how long

Synced data is stored in a PostgreSQL database hosted by Render in the
United States (Oregon). We keep it until you delete it. There is no backup
retention beyond what our hosting provider keeps for operational recovery.

Server logs contain the usual request records — timestamps, request
identifiers, error details, and IP addresses recorded by our hosting
provider's network. They are used to diagnose faults.

## Your choices

- **Use the app signed out.** Nothing is sent to us; everything stays local.
- **Download your data.** Settings → Account → "Download my cloud data".
- **Delete your account.** Settings → Account → delete. This removes your
  account and every word, deck, and membership we hold for you. Data already
  on your device stays on your device until you remove the app.
- **Avoid Google's text-to-speech** by leaving the system voice selected.

Text recognition cannot currently be turned off for horizontal and document
scans without turning off scanning of that kind of page.

## Children

BenkyoReader is not directed to children under 13, and we do not knowingly
collect information from them.

## Changes

If this policy changes materially, the effective date above changes and the
new version is published at this address before the change takes effect.

## Contact

Questions, or a request about your data: open an issue at
<https://github.com/tarekgabarin/benkyoreader-legal/issues>, or use the
support address listed on the app's App Store page.
