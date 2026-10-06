# mHealth — tutorial for testers

**Start here.** mHealth is two apps that keep a patient's health record on the
patient's own phone, and let a clinician read and add to it over local Wi-Fi.
Nothing goes to the internet, and there is no account to create.

- **Mapp** runs on the patient's Android phone and holds the records.
- **Dapp** runs on the clinician's Windows computer and reads them during a
  visit.

## Download the apps

| | Where |
|---|---|
| Dapp, for Windows | <https://github.com/jpkoc/dapp-beta/releases> |
| Mapp, for Android | <https://github.com/jpkoc/mapp-beta/releases> — or the Firebase invitation you were sent |

Install Dapp first: chapter 3 covers both, and the two have to pair with each
other before there is anything to look at.

## Being told about new versions

New releases are announced on the **mHealth-Africa** channel on WhatsApp:

<https://whatsapp.com/channel/0029VbEKtorEVccSIbVooe0L>

Follow it and you get a message whenever a new Dapp or Mapp is out. It is
one-way — you cannot reply there, and no one sees who else follows it.

Or point a phone camera at this:

<img src="mHealth-Africa-channel.png" width="180" alt="QR code for the mHealth-Africa WhatsApp channel">

## The chapters

Read them in order. Each folder holds a PDF.

1. **Background** — what the two apps are for and why they work offline.
2. **Before You Start** — what you need: a Windows computer, an Android
   phone, and a Wi-Fi network they can both join.
3. **Installation** — Dapp on the computer, Mapp on the phone.
4. **Initialization** — registering, and loading the demo family so there is
   something to practise on.
5. **First look at Dapp & Mapp** — a tour of both screens.
6. **Connecting Mapp to Dapp** — pairing the phone with the computer and
   running a visit.

## Sample records

The Dapp release includes `Dapp-Examples-<version>.zip`: notes, vitals forms
and attachments to practise with. Unzip it anywhere and attach the files from
inside Dapp.

## Versions

The tag on this repository matches the Dapp and Mapp version it was written
for. `main` is always the newest. If you are testing an older build, open the
matching tag from the branch menu above.

## Reporting problems

Tell whoever gave you this link. Useful things to include: which app, what you
were doing, what you expected, and what happened instead. Dapp keeps a log at
`Documents\Dapp\Logs\dapp-log.txt` — if something failed with a message,
that file usually has it.

These are beta builds. Expect rough edges.
