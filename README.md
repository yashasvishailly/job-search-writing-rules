# Job search writing rules

A free Claude skill. It's a deny list for anything you send while job hunting: cold DMs, cover letters, application form answers, follow-ups, referral asks.

Every job search guide tells you what to say. This one tells you what to delete.

These rules are the writing half of [The One Job](https://yashasvishailly.com/theone-jobsearch/), a paid system for finding senior roles before they get posted. The writing half is free.

## Why this exists

I've sent a lot of cold messages to founders and hiring managers who had no reason to answer me. Enough of them replied that I went back and worked out what the replying ones had in common.

The common thread was fourteen things I had stopped writing.

The biggest one: I stopped naming gaps. A job asks for an IIM degree and you don't have it, so you write "I'm not from IIM, but here's why I can still do this." The reader wasn't thinking about your degree. You've made them think about it, and you confirmed the filter applies to you. Apply anyway. Say nothing about the gap.

The rest of the rules are in [SKILL.md](SKILL.md).

## What's in it

- 14 hard rules, each with the rewrite
- A banned vocabulary list: AI tells, hedges, openers, closers, filler ([banned-words.md](banned-words.md))
- Worked before and after rewrites for five message types ([before-after.md](before-after.md))
- A 13-point pass to run before you hit send

## Install

**Claude Code / Cowork**

```bash
git clone https://github.com/yashasvishailly/job-search-writing-rules.git ~/.claude/skills/job-search-writing-rules
```

**Claude.ai**

Download the repo as a zip, then upload it under Settings, Capabilities, Skills.

Then ask Claude to write the message. The skill loads itself.

## Use it without Claude

Open [SKILL.md](SKILL.md), paste it into whatever you use, then paste your draft underneath and ask for the audit. It's plain text and it works anywhere.

## What this doesn't do

These rules are lifted straight out of The One Job, which is a paid product. I'd rather the writing half were free.

The half that stays paid is the hard half. The nightly triage of deciding which roles are worth a week of your energy. And the finding, because the good roles get filled through a conversation before they ever become a listing you can apply to.

That's what [The One Job](https://yashasvishailly.com/theone-jobsearch/) is for. It's the system I built over seven months of hit and trial to find roles before they're posted and decide which ones to spend a week on. It's paid. This skill is free and it stays free.

## Who wrote it

Yashasvi Shailly. Operator, eight years across founder's office, chief of staff and revenue operations roles at startups in India, the UK, the US and Canada. I build things at [The One Labs](https://yashasvishailly.com).

[LinkedIn](https://www.linkedin.com/in/yashasvishailly/)

## License

MIT. Take it, fork it, change it. A link back is nice and not required.
