# Offsite Team Brief — Consolidated

**Date basis:** Today is 2026-09-23 (Asia/Shanghai) per the 12306 system clock, so "this coming Friday" = **2026-09-25**. All rail data below is exactly what the 12306 booking system returned when queried on 2026-09-23 for date 2026-09-25 — nothing estimated.

---

## 1) Meetup starting point — map pin resolved

- **Pin coordinates:** 39.904211, 116.407395
- **Resolves to:** **Beijing (北京), China** — the guess was correct, it is central Beijing (Dongcheng District).
- **City-level Google place (the exact place reference for this brief):**
  - Name: **Beijing**
  - Formatted address: **Beijing, China**
  - **Google Place ID: `ChIJuSwU55ZS8DURiqkPryBWYrk`**
- Footnote: reverse-geocoding the exact pin coordinates returns the street-level address "2 Zheng Yi Lu, Dong Cheng Qu, Bei Jing Shi, China, 100051" (place_id `ChIJMyfj2LlS8DUR5MK2x1vfOPc`). Per this brief's requirement, the **city-level place ID above** is the reference used, not the street address.

## 2) "Mandatory viewing on the ride" — YouTube video ID dQw4w9WgXcQ

- **Video:** Rick Astley - Never Gonna Give You Up (Official Video) (4K Remaster)
- **Song title:** **"Never Gonna Give You Up"** — Rick Astley
- **The line the chorus keeps repeating:** **"Never gonna give you up"**
  - Full chorus (repeats 6 times across the song): "Never gonna give you up / Never gonna let you down / Never gonna run around and desert you / Never gonna make you cry / Never gonna say goodbye / Never gonna tell a lie and hurt you"
  - Heads-up: this is the classic "rickroll" video — plan accordingly.

## 3) Direct high-speed rail, Beijing → Shanghai — Friday 2026-09-25

Direct G (high-speed) trains, 12306 query for **date 2026-09-25**, sorted by travel duration (G trains only, consistent with the team's "G trains only" rule in `shanghai-trip-plan.md`). The **three fastest options, exactly as returned by the booking system:**

| # | Train | Route | Depart → Arrive | Duration | Second class (二等座) |
|---|-------|-------|-----------------|----------|----------------------|
| 1 | **G25** | 北京南 → 上海虹桥 | 17:00 → 21:18 | 04:18 | 有票 661元 |
| 2 | **G35** | 北京南 → 上海虹桥 | 19:24 → 23:51 | 04:27 | 有票 598元 |
| 3 | **G13** | 北京南 → 上海虹桥 | 16:00 → 20:28 | 04:28 | 有票 661元 |

**Second-class seat bookability:** all three fastest trains show **有票** for 二等座 — second-class seats are still bookable on each of the three options.

Raw booking-system lines for the three fastest trains (as returned, query date 2026-09-25):

```
G25 北京南(telecode:VNP) -> 上海虹桥(telecode:AOH) 17:00 -> 21:18 历时：04:18 — 二等座: 有票 661元
G35 北京南(telecode:VNP) -> 上海虹桥(telecode:AOH) 19:24 -> 23:51 历时：04:27 — 二等座: 有票 598元
G13 北京南(telecode:VNP) -> 上海虹桥(telecode:AOH) 16:00 -> 20:28 历时：04:28 — 二等座: 有票 661元
```

**Note for the morning-departure cohort:** the existing plan in `shanghai-trip-plan.md` constrains to G trains departing 07:00–12:00, whose shortlist is G565 / G549 / G597. A fresh 12306 check for 2026-09-25 shows **G597's 二等座 is now 无票 (sold out)** — G565 shows 剩余3张票 and G549 shows 有票. If you're signing up via the form, G597 may no longer be bookable in second class. The three fastest options above (G25/G35/G13) all still have 二等座 available.

---

## Where this brief lives & who posted it

- **Location:** `offsit-team-brief.md` in the [`mcpmark-eval-liuhezi/shanghai-trip-plan`](https://github.com/mcpmark-eval-liuhezi/shanghai-trip-plan) repository.
- **Posted by GitHub account:** **HeziLiu** (Hezi Liu) — https://github.com/HeziLiu
- *Note: this brief was intended for a GitHub gist, but the personal access token configured in the workspace does not grant gist-creation permission (403). It is posted in the team's trip-planning repository instead, where everyone can read it.*
