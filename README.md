# TechLift Teaching Games

A collection of lightweight, browser-based games built to be dropped into **TechLift** lessons across multiple courses. Each game turns an abstract idea from the curriculum — scoping a product, hunting bugs, building with AI, spotting fake news, structuring a pitch — into something a class can *do* in a few minutes.

## How these games work

Every game is a **single self-contained HTML file**. There is nothing to install, build, or deploy:

- **Zero setup** — open the file in any modern browser (or host it as a static page and share a link).
- **Internet connection is all you need** to run and share it.
- **No accounts, no login.**
- **No saving** — progress and scores live only in the current tab. Each session is fully self-contained; refresh and you start clean.
- **Configurable** — game content lives in a `CONFIG` block at the top of each file, so the same game can be re-themed or retuned for different courses without touching the logic.

## Two ways to play every game

Each game ships with **two modes**, chosen on the opening screen — the same game, only *who decides* changes:

| Mode | Hebrew | Who plays | How |
|------|--------|-----------|-----|
| **Class / Board** | מסלול לוח | The whole class together | Projected on the board. The instructor drives; the class votes by show of hands before each reveal. No devices needed per team. |
| **Team** | מסלול צוות | Each team on its own computer | Teams play independently at their own pace, then compare results. |

The class mode is designed as a shared, instructor-led moment; the team mode is designed for hands-on, self-paced play.

> All games are in **Hebrew**, matching the TechLift classroom.

---

## The games

### 🛒 Feature Market — שוק הפיצ'רים
**Folder:** [`budget game/`](budget%20game/index.html)

**Purpose:** Prioritization and scoping / MVP thinking. Every team gets the *same shop, the same prices, and a fixed build budget* (100 build points) — but a private wallet for their own app. Feature by feature, they decide: **buy or skip.** Skipping is a legitimate move — leftover budget stays in your pocket. The point isn't to buy the most; it's to buy only what *your* app actually needs, then defend those choices.

**Teaches:** trade-offs under constraints, resisting feature creep, and justifying product decisions.

---

### 🐛 Bug Safari — ספארי באגים
**Folder:** [`bug safari/`](bug%20safari/bug-safari.html)

**Purpose:** QA and critical-eye training. Teams explore a deliberately broken sample app seeded with planted bugs and hunt them down against the clock, documenting each finding with a suggested fix. The twist: judge the app by *its audience*, not by what's convenient — some issues are only bugs for that specific audience. Ends with a reveal, a severity map, and a debrief.

**Teaches:** structured bug-finding, writing up findings, and evaluating quality from the user's point of view.

---

### 🏗️ Build Simulator — סימולטור הבנייה
**Folder:** [`build simulator/`](build%20simulator/index.html)

**Purpose:** Building a real app *with AI*. Each turn, the team picks the next prompt to send — and the screen changes based on what they asked for. The goal: reach a working first screen before the turns run out. It rewards the **golden rule** of AI-assisted building: give full context up front, then move in focused steps — prompt, test, save — instead of chasing greedy all-at-once requests.

**Teaches:** prompting discipline, iterative development, and testing/saving as you go.

---

### 📰 The Newsroom — חדר החדשות
**Folder:** [`fake news/`](fake%20news/index.html)

**Purpose:** Media literacy and spotting misinformation. Round by round, teams weigh a story and lock in a vote *before* the truth is revealed. In class mode several groups vote around one projected board; in team mode the computer *is* your group.

**Teaches:** evaluating sources, resisting misleading framing, and thinking before sharing.

---

### 🎤 The Editing Table — שולחן העריכה
**Folder:** [`pitch assembly/`](pitch%20assembly/editing-table.html)

**Purpose:** Pitch craft and storytelling. Teams get the building blocks of an elevator pitch — shuffled — and arrange them into the strongest version, discovering how **order changes meaning.** A second round teaches that a great pitch is also about what you leave *out*. There's no single right answer: the engine scores each attempt **1–5** on ordering principles and explains *why* an order works or falls apart — mirroring the peer rating used in the lesson.

**Teaches:** narrative structure, editing for impact, and cutting to the essentials.

---

## Repository layout

```
techlift_teaching_games/
├── budget game/        # שוק הפיצ'רים — Feature Market
├── bug safari/         # ספארי באגים — Bug Safari
├── build simulator/    # סימולטור הבנייה — Build Simulator
├── fake news/          # חדר החדשות — The Newsroom
├── pitch assembly/     # שולחן העריכה — The Editing Table
└── README.md
```

## Running a game

1. Open the game's HTML file in a browser — locally (double-click) or via any static host.
2. Pick a mode on the opening screen: **Class / Board** (מסלול לוח) or **Team** (מסלול צוות).
3. Play. Nothing is saved — closing or refreshing the tab resets everything.

To share with a class, host the folder as a static site (e.g. GitHub Pages) and hand out the link.
