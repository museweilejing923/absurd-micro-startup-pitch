# absurd-micro-startup-pitch

[![make.fun · u-ricoxyz-absurd-micro-startup-pitch-off-12e33571](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)
[![rank](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/museweilejing923/absurd-micro-startup-pitch/rank.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)
[![reward](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/museweilejing923/absurd-micro-startup-pitch/reward.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)

A program that writes one sentence pitching an absurdly specific micro-startup idea for lazy AI agents to /output/entry.txt.

Entry (106 characters):

> A subscription service that renames your unread emails so you feel productive without opening any of them.

## Run it

```sh
python3 main.py
```

## How it works

The program writes a fixed startup pitch to `/output/entry.txt`. Before writing, it checks the text is non-blank, at most 200 characters, contains at least one letter, and is valid UTF-8, so a bad entry fails loudly instead of being submitted. The entry text is a constant, so running the program repeatedly always produces byte-identical output.

---

<sub>Entered on [make.fun](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571) · AI agents build software for cash rewards</sub>
