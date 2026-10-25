# bread-cubbie-skill
# Bread

**Your empty afternoons are worth money.**

Bread is a [Cubbie](https://cubbie.ai) Skill that turns the dead hours in a student's week into actual cash. It looks at when you're genuinely free, finds short **paid** opportunities that fit those gaps — paid campus research studies, one-off campus gigs, quick local side-work — and texts you only the ones worth your time, with the sign-up link and when to leave.

Built for the [Cubbie Hackathon](https://hackathon.cubbie.ai) · Track 1.

---

## The problem

Students are broke, and they're sitting on hours of free time between classes without realizing those hours are worth money. Meanwhile, universities run **paid research studies** constantly ($10–40 for 30–60 min, sometimes much more), post one-off paid gigs, and almost nobody knows where to look. The money is right there. Bread goes and gets it.

## What it does

Text Bread something like *"I'm broke and free this afternoon"* and it:

1. **Checks when you're actually free** — reads your Canvas schedule and calendar to find real gaps in the next 7 days.
2. **Finds real, paid opportunities that fit** —
   -  **Paid research studies** (SONA pools, psych/business/med departments)
   -  **One-off campus gigs** (UX testing, note-taking, event setup, survey panels)
   -  **Quick local side-work** that fits a free block
3. **Texts you the best ones** — pay, how long, when, and a one-tap sign-up link. Top 3 in the text; a full PDF list if there are more.
4. **Only if you say so** — books you in, sets a reminder 30 min before with when to leave, and scans every morning for new ones that beat your minimum pay.

Bread never asks you to pay anything, never signs you up on its own, and never touches your bank. It finds the money and hands you the link — you decide.

## Example

```
Found 3 that fit your gaps this week 

1. Psych study, $30 for 45 min
Thu 2:15pm (you're free 2–4)
sona.stateu.edu/study/4412

2. UX test for the library app, $25 for 30 min
Wed 11am
stateu.edu/ux-signup

That's ~$55 this week. Want me to remind you 30 min before each?
```

## Install

Text the link to this repo to Cubbie:

```
https://github.com/<your-username>/<your-repo>
```

Cubbie installs the Skill from `SKILL.md`. No API key and no account sign-up required — Bread works with public web search and Cubbie's browser, plus your Canvas/Google Calendar if connected (it'll ask once, or you can just tell it your free blocks).

## How it's built

A single [`SKILL.md`](./SKILL.md) written against Cubbie's Skill interface. It names the abilities it needs in plain words — reading your schedule, web search, Cubbie's browser, reminders, memory — and Cubbie runs them. Everything stays on your device; Bread remembers your school, minimum pay, and what it's already shown you.

## Team

Built for the Cubbie Hackathon 
