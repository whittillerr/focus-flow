# Focus Flow - Cold Call Tracker

A streamlined web app for tracking high-volume cold calls for AI automation sales.

## Features

- **CSV Import** - Import contacts from Clay (name, phone, website)
- **Quick Call Logging** - Log calls with outcomes (Voicemail, Interested, Not Interested, Callback)
- **Analytics Dashboard** - Track daily call volume and conversion funnel
- **Call List** - Work through imported contacts with stage tracking
- **Search & Export** - Search call history and export to CSV

## Usage

1. Open `focus-flow.html` in your browser
2. Go to **Import** tab and upload your Clay CSV file
3. Contacts auto-map (columns: name, phone, website)
4. Go to **Dashboard** tab to start logging calls
5. Track your progress with charts and stats

## Workflow

- Import 25-50 contacts per session
- Make calls from mobile phone
- Log calls on desktop after each session
- Track conversion: Cold → Warm → Demo → Closed

## Tech Stack

- Single-file HTML/CSS/JavaScript app
- localStorage for data persistence
- No external dependencies
- Works offline

## Data Structure

Contacts include:
- Phone number
- Business name
- Website
- Stage (Cold, Warm, Demo, Closed, Dead)

Call logs track:
- Timestamp
- Outcome
- Text sent status
- Notes

---

Built for efficient cold calling at scale.
