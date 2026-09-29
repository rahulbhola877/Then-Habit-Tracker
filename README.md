# Then

A calm habit tool built to be outgrown. Hook one tiny habit onto a moment you already have ("After I pour my coffee, I read two pages"). No alarms, no streaks, nothing resets.

Meet **Tally**, the mascot who asks a few questions first and tailors the app to you.

## Screens

| Screen | Where it lives |
|---|---|
| Welcome and onboarding (4 steps) | first launch |
| Tally's six questions and "how I'll help you" | after entering your name, or Settings > Answer Tally's six questions |
| Pick a moment, pick a tiny action, review | Habits > Add a habit |
| Today (hero sentence, week dots, progress) | Today tab |
| After a missed day | Today > "Why that's fine" |
| Free minutes and timer | Today > "I have a few free minutes" |
| One habit (rings, tally, weekly check-in, edit) | Habits > tap a habit |
| Graduation | when a habit gets three "yes" check-ins |
| Your habits, Shots (9 lessons), Settings and backup | tab bar and gear icon |

## Run it

It is one static file, so there is no build step.

```
npx serve .
```

## Data

Everything is saved in the browser (`localStorage`, key `then.v1`) on that device. Nothing is sent anywhere. Use Settings > Backup to copy your data between devices.

## Deploy

Connected to Vercel as a static site. Every push to `main` deploys.

## Brand

`assets/brand/` has the app icon (SVG and PNG) and Tally in six moods (SVG).
