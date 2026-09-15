<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58A6FF,100:1F6FEB&height=180&section=header&text=Yuki%20Matsukura&fontSize=50&fontColor=ffffff&fontAlignY=36&desc=CTO%20%40%20Minedia%2C%20Inc.%20%E2%80%94%20Tokyo%2C%20Japan&descAlignY=58&descSize=16" alt="Yuki Matsukura — CTO at Minedia, Inc., Tokyo, Japan" width="100%" />

[![Portfolio](https://img.shields.io/badge/Portfolio-4A90E2?style=for-the-badge&logo=githubpages&logoColor=white)](https://matsubo.github.io/)
[![Blog](https://img.shields.io/badge/Blog-FF5722?style=for-the-badge&logo=rss&logoColor=white)](https://blog.teraren.com/)
[![Zenn](https://img.shields.io/badge/Zenn-3EA8FF?style=for-the-badge&logo=zenn&logoColor=white)](https://zenn.dev/matsubokkuri)

</div>

---

I lead technology at **[Minedia, Inc.](https://corporate.minedia.com/)**, a data-technology startup in Tokyo — strategy, architecture, and the engineering team behind it. Earlier: social gaming platform development at **GREE**, and **SPIKE**, a zero-fee payment service, at **Metaps**.

Day to day I build **LLM-powered products** and **small, sharp APIs** for Japanese open data. Two patents, a Springer-published paper on regional EC data analysis, and open source since 2009.

> **[Full portfolio →](https://matsubo.github.io/)** — research, patents, experience, and every project in detail.

---

## What I'm shipping

- **[voice-memo-stt](https://github.com/matsubo/voice-memo-stt)** `Go`<br />Transcribe macOS Voice Memos via pluggable STT engines — CLI, TUI and Alfred Workflow.
- **[agent-skills](https://github.com/matsubo/agent-skills)** `Shell`<br />Personal Claude Code skills, shipped as a plugin marketplace.
- **[scope1090](https://github.com/matsubo/scope1090)** `Python`<br />ADS-B receiver dashboard — ECharts, SQLite time-series, minimal SD-card writes.
- **[astro-affiliate-card](https://github.com/matsubo/astro-affiliate-card)** `TypeScript`<br />Amazon / Rakuten / Yahoo! product cards for Astro *(also as a [remark plugin](https://github.com/matsubo/remark-affiliate-card))*.
- **[claude-code-max-usage](https://github.com/matsubo/claude-code-max-usage)** `Shell`<br />Track Claude Code Max plan usage from the shell.

---

## Featured Projects

Messy Japanese public data, normalized and served as JSON. Free, no account, no rate limit, behind a CDN.

```console
$ API=https://postcode.teraren.com
$ curl -s $API/postcodes/1600023.json \
    | jq '{city_roman, suburb_roman}'
{
  "city_roman": "Shinjukuku",
  "suburb_roman": "Nishishinjuku"
}
```

| Open data API | What it serves |
| :--- | :--- |
| **[postcode.teraren.com](https://postcode.teraren.com/)** | Postal codes, prefectures and addresses |
| **[bank.teraren.com](https://bank.teraren.com/)** | Banks and their branches |
| **[corporation.teraren.com](https://corporation.teraren.com/)** | Corporate numbers and registered entities |
| **[train.teraren.com](https://train.teraren.com/)** | Railway lines and stations |
| **[school.teraren.com](https://school.teraren.com/)** | Schools across the country |
| **[dam.teraren.com](https://dam.teraren.com/)** | Dams and reservoirs |
| **[seireki.teraren.com](https://seireki.teraren.com/)** | Japanese era ⇄ Gregorian dates |

| AI product | What it does |
| :--- | :--- |
| **[AI Moderator](https://ai-moderator.teraren.com/)** | A realtime speech model that runs qualitative research interviews |
| **[Triathlon AI Analyzer](https://ai-triathlon-result.teraren.com/)** | Race result analysis and pacing insight |

| Browser tool | What it does |
| :--- | :--- |
| **[SOTA Peak Finder](https://matsubo.github.io/sota-peak-finder/)** | Summits worldwide, works offline anywhere |
| **[Offline QTH](https://matsubo.github.io/offline-qth/)** | Maidenhead grid locator with no network |
| **[Marathon Pace](https://matsubo.github.io/marathon-pace/)** | Splits and finish-time calculator |
| **[Inkan Generator](https://inkan.teraren.com/)** | Generate a one-of-a-kind seal in the browser |

---

## Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=ruby,rails,ts,go,python,react,astro,nodejs,postgres,aws,cloudflare,docker&perline=6" alt="Ruby, Rails, TypeScript, Go, Python, React, Astro, Node.js, PostgreSQL, AWS, Cloudflare, Docker" />

Going deep right now on **LLM application architecture**, **OpenAPI-first microservices**, and **self-hosted PaaS**.

</div>

---

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=matsubo&theme=tokyonight" alt="Profile details: contributions, public repos and join date" width="100%" />

<img src="https://streak-stats.demolab.com?user=matsubo&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="GitHub contribution streak" height="170" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=matsubo&theme=tokyonight" alt="Repositories per language" height="170" />

</div>

<details>
<summary><b>Longest-running open source</b></summary>

<br />

| Repo | Stars | What it is |
| :--- | :--- | :--- |
| [emoji-sprite](https://github.com/matsubo/emoji-sprite) | 29 | CSS sprite and icons for emoji |
| [redis-ranking](https://github.com/matsubo/redis-ranking) | 21 | Redis sorted-set wrapper specialised for rankings |
| [matsu-shell-setting](https://github.com/matsubo/matsu-shell-setting) | 11 | My shell dotfiles |
| [spike-ruby](https://github.com/matsubo/spike-ruby) | 9 | SPIKE payment API client for Ruby |

</details>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6FEB,100:58A6FF&height=120&section=footer" alt="" width="100%" />

</div>
