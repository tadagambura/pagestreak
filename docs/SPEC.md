# PageStreak: Spec

**Read a little every day** · #7 of 31 · Wave 1: Daily keepers · Used: Daily · Easy · Revenue potential: Medium · Habits, Health & Learning · Source: New (Claude)

## One-liner

Log the pages or minutes you read each day, keep a reading streak, track your books and a yearly goal, and get a shareable reading recap. Duolingo-style streaks applied to reading.

## Problem / audience

- **Who it's for:** Readers who want to read more, especially anyone with a yearly book goal.
- **The problem it solves:** People want to read more but lose the habit, and most reading apps are social networks first.
- **Example:** Aiming for 24 books this year, a user logs 15 pages before bed, keeps a 40-day streak, and shares their monthly recap.

## MVP features (ship with only these)

1. Log pages or minutes in one tap
2. Daily streak with freezes
3. Currently reading list and a yearly goal
4. Monthly and yearly recap cards
5. Reminder at the user's reading time

## Not in MVP

- Book search using an open book database
- Reading challenges
- Stats and themes

## Monetisation

| Model | Detail |
|---|---|
| Free | Logging, streaks and a goal, with ads |
| Premium | £1.99/month or £14.99 lifetime: stats, challenges, themes, recap styles |
| Affiliate | Book links, clearly labelled |

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Reading-time reminder |
| Tiny win | Log pages |
| Progress | Streak, goal progress, books finished |
| Share | Monthly and yearly recaps |
| Next step | When a book is finished, prompt for the next one |
| Cadence | Daily |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone: five signature animations

**Playful.** Celebrations, confetti, cute characters, satisfying sounds and mild comic reactions. Nothing tragic.

- Skipped a day: the page rips in half dramatically, then gets taped back together when you read
- Pages logged: the pages flutter and the bookworm munches through them
- Book finished: the book slams shut in a puff of dust and the bookworm wears a graduation cap
- Yearly goal hit: books stack into a staircase and the bookworm climbs it
- Late-night reading: the bookworm in a nightcap with a tiny torch


## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app.
- **Data:** On the device only.
- **Backend:** None for the free version: everything lives on the phone. Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Reading habits; Book recaps; Reading challenges
- **Shareable output:** Monthly and yearly recaps

## Risks

Goodreads and StoryGraph are big. Stay focused on the reading habit, not a book social network.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to the Growth & Maintenance Engine as an app config
