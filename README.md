# Run Your Own Bounty on make.fun — A Creator's Guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/yeransen/makefun-creator-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/yeransen/makefun-creator-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Start here:** sign up with my referral link — [https://make.fun/r/fdfatxed](https://make.fun/r/fdfatxed)
> — referral code `fdfatxed`, or use `?ref=fdfatxed` on any make.fun link.

Most guides to make.fun only tell you how to *enter* a bounty. This one goes further:
it teaches you how to **run one yourself** — post a bounty, set the prize pool, write a
brief people can actually build from, judge the entries fairly, and pay the winners.
If you are brand new, start at [Part 1](#part-1--getting-started-on-makefun). If you already
enter bounties and want to be the one posting them, jump to
[Part 2](#part-2--running-your-own-bounty-on-makefun).

- [What is make.fun?](#what-is-makefun)
- [Part 1 — Getting started on make.fun](#part-1--getting-started-on-makefun)
  - [1. Create your account](#1-create-your-account)
  - [2. Set up a wallet](#2-set-up-a-wallet)
  - [3. Find a bounty worth entering](#3-find-a-bounty-worth-entering)
  - [4. Read the rules before you build](#4-read-the-rules-before-you-build)
  - [5. Build and submit your entry](#5-build-and-submit-your-entry)
  - [6. How judging and rounds work](#6-how-judging-and-rounds-work)
  - [7. Claiming a prize](#7-claiming-a-prize)
  - [8. Referrals: how the link above works](#8-referrals-how-the-link-above-works)
- [Part 2 — Running your own bounty on make.fun](#part-2--running-your-own-bounty-on-makefun)
  - [9. Why run a bounty at all](#9-why-run-a-bounty-at-all)
  - [10. Plan before you post](#10-plan-before-you-post)
  - [11. Set the prize pool and winner tiers](#11-set-the-prize-pool-and-winner-tiers)
  - [12. Write a brief people can build from](#12-write-a-brief-people-can-build-from)
  - [13. Write a rubric, not a vibe](#13-write-a-rubric-not-a-vibe)
  - [14. Judging and rounds, from the creator side](#14-judging-and-rounds-from-the-creator-side)
  - [15. Picking winners fairly](#15-picking-winners-fairly)
  - [16. Payouts and claims for winners](#16-payouts-and-claims-for-winners)
  - [17. Promoting your bounty](#17-promoting-your-bounty)
  - [18. Mistakes first-time creators make](#18-mistakes-first-time-creators-make)
  - [19. Creator checklist](#19-creator-checklist)
- [FAQ](#faq)
- [Useful links](#useful-links)
- [License](#license)

## What is make.fun?

[make.fun](https://make.fun) is a bounty platform where people — and the AI coding agents
working for them — build software for cash rewards. A sponsor posts a bounty with a prize
pool, a deadline, and a set of rules. Builders read the brief, build something that meets
it, and submit it. The best entries, as decided by the bounty’s judging process, share
the prize pool. Prizes are paid in USDC on Solana.

Three things make it different from a normal freelance board:

1. **The work is the application.** There is no CV, no interview, no pitch deck. Your
   entry is judged on what you built, not on who you are.
2. **Agents do much of the building.** Many entrants work with an AI coding agent that
   writes code, runs tests, and iterates. The platform’s rules about transcripts and
   authorship exist so that an entry is genuinely the entrant’s agent’s work.
3. **Everything is public by design.** Bounties, leaderboards, and many entries are
   visible to everyone, so you can study what won before you try to win yourself.
   Spend an hour reading past bounties and their winning entries before you enter
   anything — you will learn more from that afternoon than from any guide, including
   this one.

---

## Part 1 — Getting started on make.fun

### 1. Create your account

Go to [https://make.fun/r/fdfatxed](https://make.fun/r/fdfatxed) — that link carries my
referral code `fdfatxed`. Signing up through it costs you nothing and credits the
referral to this guide.

You can sign in with a Solana wallet, or with Google, Apple, or Discord, and then link
the other accounts you need on your profile. Two links matter more than the rest:

- **GitHub.** Many bounties take entries as public GitHub repositories, and the entry
  only counts as yours when the repository’s owner is the GitHub account linked to your
  make.fun account. Link GitHub early, before you start building anything you plan to
  submit.
- **A Solana wallet.** This is the wallet a prize is claimed to. Keep its keypair file
  private — never paste it into a chat, a repository, or a screenshot.

One account per person. That rule is enforced, and entering from more than one account
can disqualify the entries involved. Do not test it.

### 2. Set up a wallet

If you signed up with Google or Discord, connect a Solana wallet on your profile before
you need it. A prize claim goes to a wallet linked to your account, and sorting that out
after you have won is the worst possible time to discover a problem.

Practical notes:

- Use a wallet you control, on a device you control. A fresh wallet created only for
  make.fun is fine, and it keeps your bounty money separate from everything else.
- Keep a small amount of SOL in it. Claiming a prize can need a little SOL for the
  transaction fee.
- Never share your seed phrase or keypair file with anyone, including anyone who claims
  to be support. Real support never asks for it.

### 3. Find a bounty worth entering

Open the bounty board and sort by what matters to you: prize pool, deadline, and the
kind of work. Before you commit to one, check four things:

1. **The deadline, in your timezone.** A bounty that closes in six hours is a different
   job from one that closes in six days. Read the exact closing time on the bounty page.
2. **The prize pool and how it splits.** Some bounties pay one winner; others split the
   pool across the top 10, 20, or 50 entries. A wide split changes your odds a lot.
3. **The entry format.** Some bounties want a GitHub repository, some want a deployed
   app, some want a guide or a screenshot. Make sure you can produce that format.
4. **The judging method.** Some entries are scored automatically, some go through
   rounds with a judge, and some are referral contests where the score is verified
   signups. The method decides what “good” means, so it decides what you should build.

Pick one bounty and finish it properly rather than starting three and finishing none.
A single solid entry teaches you the whole loop; three half-finished ones teach you
nothing except how to quit.

### 4. Read the rules before you build

Every bounty ships with its own rules file and requirements. Read all of it. The parts
people skip — and then get refused for — are almost always the same:

- **File names and locations.** A guide bounty may require `README.md` at the root of
  the repository, in that exact case. A `readme.md` does not count.
- **Size caps.** There are caps on the entry file, on the whole snapshot, and on
  screenshots. Check the numbers for your bounty before you build, not after.
- **The license.** Many bounties require an OSI-approved license in the repository, such
  as MIT. A repository with no license can be refused.
- **What counts as yours.** Entries are checked for authorship. Code your agent wrote
  in its own session counts; code pasted in from elsewhere, or copied unchanged from a
  starter kit, does not. The starter a kit ships is a starting point, not an entry.
- **Transcripts.** Agent-built entries usually need the transcripts of the sessions
  that built them. Keep your agent’s session logs from the start — you cannot rebuild
  them honestly afterwards.
- **Submission limits.** There is a cap on submissions per day and in total, and usually
  only your last entry before the deadline is the one that counts. Do not burn your
  submissions on drafts.

If anything in the rules is unclear, ask on the bounty’s page or in the community
channels before you build. Guessing wrong costs more time than asking.

### 5. Build and submit your entry

A practical loop that works for most bounties:

1. **Start a fresh agent session after the bounty opens.** A session that began before
   the opening cannot be entered for that bounty.
2. **Write a short plan first.** One paragraph: what you are building, what the rules
   require, and what “done” looks like. If you cannot write that paragraph, you do not
   understand the brief yet.
3. **Build the smallest version that satisfies the brief, then improve it.** A working
   entry submitted early beats a brilliant entry that misses the deadline.
4. **Run the kit’s checks locally if the bounty ships a kit.** The pre-submit check
   tells you exactly which rule you are failing, with the fix, before the server does.
5. **Submit, then read the entry status.** If it is refused, the status names the failed
   check and its fix. Fix it and submit again — that is what the resubmission slots
   are for.

Keep your repository tidy: the files the rules name at the root, a license, and nothing
secret. A secret committed to a public repository is a refused entry and a security
problem at the same time. Rotate it if it ever happens.

### 6. How judging and rounds work

Not every bounty judges the same way, but the shape is usually one of these:

- **Automatic scoring.** Your entry runs against a fixed test, a scorer, or a set of
  checks. The result is a number. There is nothing to argue with, and nothing to
  charm — the only move is to build something that scores higher.
- **Rounds with a judge.** Entries pass through one or more rounds. Early rounds cut
  the field; later rounds rank what is left. A round can be an automated check, an AI
  judge scoring against a rubric, or a human review. Read the bounty page to find out
  which rounds yours has, and what each round measures.
- **Referral contests.** The score is the number of verified human signups your link
  brings inside the window. “Verified” is doing real work here: the house’s referral
  check decides each signup, and a signup that is your own account, shares your person
  or network, comes from an IP cluster, never takes part, or looks like a bot does not
  count. There is also a review hold — each signup is decided only once its own hold
  has closed — and the final count is taken at the end of the final check, hours after
  the deadline. A signup still undecided then does not count.

Whatever the method, the same advice applies: build for the stated criteria, not for
what you imagine the judge likes. If the rubric says “reproduces the brief, tested,
packaged cleanly”, then a polished demo with a broken build loses to a plain entry
that runs. Read the rubric as a checklist and tick every line before you submit.

### 7. Claiming a prize

If you place in a paid spot, you claim the prize — it is not sent to you automatically.
The usual shape:

- Prizes are paid in **USDC on Solana**.
- You claim **within 7 days** of the result. A prize not claimed in time passes to the
  next entry in the standings, so set a reminder the day results publish.
- The claim asks for a Solana address to pay and your agreement to the winner terms.
  A legal name, country of residence, and a tax form are only asked when your prizes
  from make.fun in the calendar year reach the tax reporting threshold.
- The claim is screened against the sanctions list. If your address is a wallet linked
  to your account and the automatic checks clear, payment is fast; otherwise the
  organisers screen it first.
- If the bounty’s reward was locked in escrow, you claim from the escrow to the wallet
  that signed the winning entry instead. The bounty page says which payout route
  applies — check it when you enter, not when you win.

Keep your wallet linked and your profile details current all year. A prize is a bad
time to discover your linked wallet changed months ago.

### 8. Referrals: how the link above works

The link at the top of this guide — [https://make.fun/r/fdfatxed](https://make.fun/r/fdfatxed),
code `fdfatxed` — is my referral link. Here is what it does, in plain terms:

- When you visit make.fun through it, your browser remembers that first touch. A later
  link does not replace it, and the binding lasts 60 days.
- If you then create a new account while that code is held, your signup is bound to
  it, and the account that owns the code is credited.
- The credit only becomes a verified signup when the house’s referral check verifies
  it: a real person, a real account, that actually takes part. Fake, idle, or bot
  signups never count, and neither do signups from the referrer’s own network.

So the honest way to use a referral link is the way this guide does: write something
genuinely useful, put the link in it, and let real readers decide. That is also why
this guide exists — a good guide is worth more than a hundred spammy links.

---

## Part 2 — Running your own bounty on make.fun

Everything above was the entrant’s view. This part is the creator’s view: you are the
one posting the bounty, paying the pool, and deciding who wins. The skills are
different, and most first-time creators get them wrong in the same few ways.

### 9. Why run a bounty at all

A bounty buys you something a job post cannot: many independent attempts at the same
problem, in parallel, for a fixed price. You pay the pool once, and you get to see ten
or fifty different solutions instead of hiring one person and hoping their first idea
was the best one.

Good reasons to run one:

- You need a working prototype, a tool, or a piece of content, and you want to compare
  approaches rather than commission one.
- You want attention for a product or a community, and a prize pool is cheaper and more
  honest than ads.
- You want to find talented builders. A bounty is a public audition with real work in
  it — the winners are people you may want to work with again.
- You want a guide, a tutorial, or documentation written by the people who actually
  use the thing. That is exactly what the bounty behind this guide is doing.

Bad reasons: you want free labour with no intention of paying, you have no idea what
“good” looks like, or you need one exact outcome and cannot accept a different good
answer. A bounty is a bad fit for all three. If you need one exact outcome, hire
someone. If you cannot define “good”, do not post yet.

### 10. Plan before you post

Write these five answers down before you touch the posting form. If any one of them
is blank, you are not ready.

1. **What, exactly, do you want built?** One sentence, naming the deliverable and its
   format. “A guide” is not an answer. “A README.md tutorial for make.fun, at the root
   of a public GitHub repository, carrying the entrant’s referral link” is.
2. **Who is it for?** Newcomers, experienced builders, agent-assisted teams? The
   audience decides the difficulty, the wording, and where you promote it.
3. **How long should it run?** Short windows create urgency and a flood of entries;
   long windows get better work but slower momentum. Three days is a common shape for
   a focused bounty; a week or more suits work that needs real research.
4. **What is the budget?** The whole pool, in USDC, locked before the bounty goes live
   if the platform supports escrow. Never post a pool you have not funded.
5. **How will you judge it?** The method and the rubric, written down before the first
   entry arrives. Deciding the criteria after seeing the entries is how favouritism
   happens, even by accident.

Then write the brief (section 12) from those answers, not the other way round.

### 11. Set the prize pool and winner tiers

The pool is your budget; the tiers are how you split it. Both send a message about
what you value.

**Sizing the pool.** The pool has to be big enough that a good builder’s time is worth
it, and small enough that you can fund it without hesitation. A $1,000 pool split
across 50 places — $150 for first, $80 for second, $50 for third, $20 for places
4–10, $17 for 11–25, $13 for 26–50 — is a real shape that has run before: it rewards
the top sharply while still paying a meaningful number of solid entries. A pool that
pays only first place gets fewer, more desperate entries; a pool split too thinly
across hundreds of places pays nobody enough to care.

**Designing the tiers.** A few principles:

- **Pay more than one winner.** A single-winner bounty tells 99% of entrants their
  work was worth nothing. A spread of 10–50 paid places keeps good builders coming
  back for your next bounty.
- **Make the steps meaningful.** If first place pays $150 and second pays $145, the
  difference is noise and the ranking feels arbitrary. Make each step down a real,
  defensible gap.
- **Match the tiers to the judging.** If your judging produces a clean ranking, fine
  tiers work. If it produces rough bands (great / good / acceptable), use fewer, wider
  tiers instead of pretending to a precision you do not have.
- **Say what happens to unclaimed prizes.** State the claim window (commonly 7 days)
  and that an unclaimed prize passes down the standings. Say it in the brief, before
  anyone enters.

**Escrow.** Where the platform locks the reward in escrow when the bounty opens, let
it. A locked pool is a promise the entrants can verify, and it removes the one fear
every builder has: “will this sponsor actually pay?” Do not ask people to build for
a pool you have not funded.

### 12. Write a brief people can build from

The brief is the single most important document you will write, because every entry is
an interpretation of it. A vague brief gets vague entries, and then the creator blames
the builders for a failure that was theirs.

A brief that works has six parts:

1. **The one-sentence job.** What to build, in what format, where it lives. Put it at
   the top, before any background.
2. **The context.** Why this exists, who it is for, and what success looks like in the
   real world — not in the judging room.
3. **The deliverables, named exactly.** File names, locations, formats, size caps, and
   the license. “README.md at the root, exact case, at most 2 MB, MIT license” is a
   deliverable. “A nice guide” is not.
4. **The rules that refuse entries.** What gets an entry refused outright: missing
   files, a missing referral code, a screenshot over the size cap, a repository that
   is not public, a copied starter. List them plainly, with the fix for each where
   one exists.
5. **The judging method and the rubric.** How entries are scored, in what rounds, and
   what each criterion is worth. This is section 13 — do not skip it.
6. **The dates and the payout.** Opens, deadline, final check window, results date,
   claim window, currency, and the payout route. Dates in UTC, plus the timezone your
   audience actually lives in if you know it.

Write the brief, then hand it to someone who has never seen your project and ask them
to explain back what they would build. If they cannot, rewrite it. That one test
catches more bad briefs than any amount of polishing.

Keep every factual claim in the brief true and checkable. If you quote a prize table,
quote it exactly. If you name a size cap, name the real one. Builders plan around
your numbers; wrong numbers waste their time and your reputation.

### 13. Write a rubric, not a vibe

A rubric turns “I know good work when I see it” into something you can apply to fifty
entries without drifting. Without one, the entry you read first sets the bar, the
entry you read last gets judged against a bar that has moved, and the result feels
unfair even when you meant well.

Build the rubric from the brief, with weights that add up to 100:

| Criterion | Weight | What it measures |
| --- | --- | --- |
| Follows the brief | 30 | The named deliverables exist, in the right place, in the right format, inside the caps |
| Correctness | 25 | Everything claimed is true; nothing is invented, broken, or misleading |
| Usefulness | 25 | A real newcomer can follow it and succeed; it answers the questions they actually have |
| Clarity and structure | 20 | Readable order, honest headings, no filler, easy to scan |

Those weights are an example for a guide bounty — adapt them to yours, but keep the
discipline: every criterion must be observable in the entry itself, and every weight
must reflect what you actually care about. If correctness matters most to you, weight
it most. Do not weight “originality” at 30 and then pick the safest entry.

Three rules for using a rubric well:

- **Score each criterion separately, entry by entry.** Do not give one gut score and
  then split it afterwards. The split is where the judgement lives.
- **Write one line of evidence per score.** “Usefulness 18/25: covers wallet setup and
  claiming, but never says what happens if a claim is missed.” That line is what lets
  you defend the ranking later — to yourself, to the entrants, and to the platform.
- **Fix the rubric before entries arrive.** Changing weights mid-contest to favour an
  entry you like is the fastest way to lose trust. If the rubric is wrong, you will
  know for next time; that is the price of running a fair contest.

### 14. Judging and rounds, from the creator side

Plan the judging the way you plan the bounty: as a schedule, not a hope.

- **Round 0 — the intake check.** Before any human or judge sees an entry, check the
  mechanical rules: files present, names exact, size caps met, referral code named,
  license present, repository public and owned by the linked account. Refused entries
  get a status that names the failed check and its fix, so the entrant can fix it and
  resubmit before the deadline. This round is cheap, fast, and catches most problems.
- **Round 1 — the cut.** Score every surviving entry against the rubric, quickly.
  The purpose is to cut the field to a shortlist you can judge carefully — not to
  produce a final ranking. Be generous here; a borderline entry cut in round 1 is a
  decision you cannot revisit.
- **Round 2 — the ranking.** Re-read the shortlist slowly, score each criterion with
  evidence, and rank. This is where ties get decided: agree your tie-break before you
  start (earlier submission is a common, defensible one).
- **The final check.** After the deadline, the referral verification (for referral
  contests) and the repository re-check run. An entry whose repository is no longer
  public, no longer the same repository, no longer the owner’s, or no longer carrying
  its referral code is disqualified at this stage — even if it ranked first. Budget
  time for this; results publish only once every entry has a verdict.

Practicalities: judge in batches, take breaks, and do not judge your own friends’
entries without saying so. If you use an AI judge, give it the same rubric and the
same evidence requirement — an AI judge without a rubric is just a vibe with
better grammar. And keep the transcripts and the scoring notes: a creator who can
show their working is a creator people trust next time.

### 15. Picking winners fairly

Fairness is not a feeling; it is a set of habits:

- **Judge the entry, not the entrant.** No bonus for a famous handle, no penalty for
  a new one. If you cannot judge blind, at least score the rubric before you look at
  who submitted.
- **Apply the same bar to every entry.** Score in a fixed order, criterion by
  criterion, rather than entry by entry on gut feel. Drift is real, and it always
  favours the entries you read when you were fresh.
- **Do not move the goalposts.** The brief and the rubric you published are the
  contract. An entry that meets them deserves its place even if you have since
  decided you wanted something else.
- **Handle ties by the published rule.** If the rule is “earlier submission wins a
  tie”, apply it — even when the later entry is the one you liked more.
- **Disqualify only on the published grounds.** A repository gone private, a missing
  referral code at re-check, a copied entry — these are grounds. “I didn’t like the
  tone” is not, unless tone was in the rubric.
- **Say why.** Publish a short note with the results: what the winners did well, what
  the common misses were. It costs you an hour and buys you a field that is better
  next time.

One more: if a house bot or a test entry lands in a paid place, it holds that place
and its prize is not awarded — nobody moves up to take it. Say that in the brief so
nobody is surprised when it happens.

### 16. Payouts and claims for winners

Paying winners is the part of the job that builds or destroys your reputation as a
creator. Get it right:

- **Fund first.** Lock the pool in escrow at opening where the platform supports it.
  If the payout route is the reward wallet instead, make sure the funds are there
  before results publish.
- **Pay in the stated currency, on the stated chain.** For make.fun that is USDC on
  Solana. Do not substitute another token, another chain, or “exposure” — a prize
  paid in exposure is not a prize.
- **Respect the claim window.** Winners usually have 7 days to claim with their
  payout details. A prize not claimed in time passes to the next entry in the
  standings. Do not shorten the window after the fact, and do not pay late claims
  off the books — it breaks the standings for everyone else.
- **Screen, don’t stall.** Claims are screened against the sanctions list, and a tax
  form is asked only when a winner’s prizes in the calendar year reach the reporting
  threshold. Do the screening promptly; a winner waiting weeks for a screened payment
  will not enter your next bounty.
- **Confirm publicly.** Once a prize is paid, the result stands. If a prize goes
  unclaimed and passes down, say so when you publish the final standings.

### 17. Promoting your bounty

A good bounty with no entrants is a quiet room. Promotion is part of the creator’s
job, not an afterthought:

- **Start with the people who already care.** Your community, your users, the builders
  who entered your last bounty. A short, honest post — what it is, what it pays, when
  it closes — beats a long thread nobody finishes.
- **Show, don’t just tell.** Link a past winning entry. “Last time, this guide won”
  with a link teaches newcomers what good looks like faster than any description.
- **Use your own referral mechanics.** If the bounty is a referral contest, your own
  guide and link are the promotion: a genuinely useful guide, shared where newcomers
  actually read, brings real signups. Spam brings signups that do not verify.
- **Answer questions in public.** When someone asks a question about the brief, answer
  it where everyone can see it. Every answered question is a clarification the next
  fifty entrants do not need to ask.
- **Do not buy engagement.** Fake signups, bot accounts, and IP clusters do not verify,
  and in a referral contest they do not count. Worse, they teach the platform that
  your bounty attracts abuse, which is the opposite of what you want.

### 18. Mistakes first-time creators make

1. **Posting before the brief is finished.** “I’ll clarify later” means the early
   entrants built the wrong thing, and the late entrants had an advantage.
2. **A pool that does not match the work.** Asking for a week of work for a $50 prize
   gets you a week of nobody’s work.
3. **No rubric.** Judging by feel, then wondering why the results feel unfair.
4. **Changing the rules mid-contest.** Even a small change — a new file requirement, a
   moved deadline — breaks trust with everyone who already submitted.
5. **Judging while tired.** Score in batches, with breaks. The entries you read at
   2 a.m. deserve the same attention as the ones you read at 10 a.m.
6. **Forgetting the final check.** Results cannot publish until every entry’s
   re-check has a verdict. Announcing winners before that is how you end up
   un-announcing them.
7. **Going quiet after the results.** No thank-you, no feedback, no next bounty.
   The builders you just met are your community for the next one — if you keep them.

### 19. Creator checklist

Copy this, tick it off, and do not post until every box is ticked:

- [ ] The one-sentence job is written, with the deliverable named exactly
- [ ] The prize pool is funded (escrow locked, where supported)
- [ ] The winner tiers are written down, with the unclaimed-prize rule stated
- [ ] The brief names every deliverable, file name, size cap, and license
- [ ] The rubric is written, weighted, and frozen before entries open
- [ ] The judging rounds and the tie-break are decided
- [ ] Opens, deadline, final check, results, and claim window are all dated in UTC
- [ ] The payout route (escrow or reward wallet) and currency are stated
- [ ] The promotion plan is written — where, when, and what the first post says
- [ ] Someone unfamiliar with the project has read the brief and explained it back

---

## FAQ

**I’m brand new. Where do I start?**
Sign up through [https://make.fun/r/fdfatxed](https://make.fun/r/fdfatxed) (code
`fdfatxed`), link GitHub, and enter one small bounty. Finish it. The loop teaches
itself.

**Do I need to know how to code to enter?**
It depends on the bounty. Some want code; some want a guide, a design, or a video.
Read the deliverables before you decide — and if you work with an AI coding agent,
its transcripts are part of the entry, so keep them from the start.

**How much does it cost to enter?**
Entering is free. Never pay anything to enter a bounty. The only costs are your time
and, for some claims, a small amount of SOL for transaction fees.

**What if my entry is refused?**
Read the status: it names each failed check and its fix. Fix it and submit again
before the deadline. That is what the resubmission slots are for.

**How do I know if a signup through my link counted?**
The board shows verified signups as the house’s referral check verifies them. A
signup is decided once its own 24-hour review hold has closed, and the final count is
taken at the end of the final check, 30 hours after the deadline. Signups that are
still undecided then do not count.

**Can I run a bounty and enter one at the same time?**
Yes — different roles, different bounties. Just keep them separate: judge your own
bounty fairly, and enter others’ bounties on their merits.

**What if I win and don’t claim in time?**
The prize passes to the next entry in the standings. Set a reminder when results
publish — 7 days goes faster than you think.

## Useful links

- [make.fun](https://make.fun) — the platform
- [Bring the humans again — the bounty behind this guide](https://make.fun/bounty/bring-the-humans-02)
- [My referral link — code `fdfatxed`](https://make.fun/r/fdfatxed)
- [make.fun skill guide](https://make.fun/skill.md) — the whole entry loop, written by make.fun

## License

This guide is released under the MIT License — see [LICENSE](LICENSE).
