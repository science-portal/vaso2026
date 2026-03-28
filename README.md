# VA Division A Science Olympiad — Student Portal

A self-contained student study portal for the **2025–2026 Virginia Association of Science Olympiad (VASO) Division A** season, built for Grades 3–4 competitors. All content is sourced directly from the official VA Division A Tournament Rules Manual v9.01.

**Live site:** `https://yourusername.github.io/your-repo-name/`

---

## What's Included

### Build Events (4)

| Event | Page | Highlights |
|---|---|---|
| 🌉 Bridge Building | `bridge.html` | Truss types, scoring formula, shopping list, practice test |
| 🗼 Tower Building | `tower.html` | Tower types, stability concepts, checklist, practice test |
| 🚀 Astronaut Lander | `lander.html` | Forces, microgravity, parachute physics, practice test |
| 🥚 Bungee Egg Drop | `bungee.html` | GPE/KE/EPE, rubber band design, scoring, practice test |

### Written Events (4)

| Event | Page | Highlights |
|---|---|---|
| 🌊 Ocean Science | `ocean.html` | Ocean zones, currents, food webs, 2 test levels |
| 📊 Data Investigations | `data.html` | Graphs, variables, mean/median/mode, practice test |
| 🧠 Nervous System | `nervous.html` | Neurons, CNS/PNS, sensory organs, practice test |
| ⚡ Shock Value | `shock.html` | Ohm's Law, circuits, breadboard build, practice test |

---

## Features

- **10 tabs per build event** — Overview, Materials, Scoring, Study Guide, Build Strategy, Tips, Slides, Shopping List, Checklist, Practice Test
- **4 tabs per written event** — Overview, Topics, Vocabulary, Practice Test
- **Auto-graded practice tests** — Multiple choice, True/False, and fill-in-the-blank with instant feedback
- **Interactive shopping lists** — Walmart-specific with aisle locations, checkboxes, and live subtotal
- **Pre-competition checklists** — Clickable items covering rules, gear, and strategy
- **Study slides** — PDF and editable `.pptx` downloads for every event
- **Light / dark mode** — Persists across all pages via `localStorage`
- **Fully responsive** — Works on desktop, tablet, and mobile
- **No dependencies** — Pure HTML, CSS, and vanilla JavaScript. No frameworks, no build step, no server required

---

## File Structure

```
/
├── index.html                          # Home page — event cards + about section
├── bridge.html                         # Bridge Building
├── tower.html                          # Tower Building
├── lander.html                         # Astronaut Lander
├── bungee.html                         # Bungee Egg Drop
├── ocean.html                          # Ocean Science
├── data.html                           # Data Investigations
├── nervous.html                        # Anatomy — Nervous System
├── shock.html                          # Shock Value
│
├── slides/                             # Study slide decks (PDF)
│   ├── Bridge_Building_StudySlides.pdf
│   ├── Tower_Building_StudySlides.pdf
│   ├── Tower_Building_ProjectSlides.pdf
│   ├── Bungee_Egg_Drop_StudySlides.pdf
│   ├── Bungee_Egg_Drop_ProjectSlides.pdf
│   ├── Astronaut_Lander_StudySlides.pdf
│   ├── Astronaut_Lander_ProjectSlides.pdf
│   ├── Data_Investigations_StudySlides.pdf
│   ├── Ocean_Study_Slides_3rdGrade.pdf
│   └── Ocean_Olympiad_StudySlides.pdf
│
├── pptx/                               # Editable PowerPoint versions
│   ├── Bridge_Building_StudySlides.pptx
│   ├── Tower_Building_ProjectSlides.pptx
│   ├── Bungee_Egg_Drop_ProjectSlides.pptx
│   ├── Astronaut_Lander_ProjectSlides.pptx
│   └── Data_Investigations_StudySlides.pptx
│
└── tests/                              # Standalone test and instruction pages
    ├── Bungee_Egg_Drop_Test.html
    ├── Bungee_Egg_Drop_Instructions.html
    ├── Astronaut_Lander_Test.html
    ├── Astronaut_Lander_Instructions.html
    ├── Tower_Building_Test.html
    ├── Tower_Instructions.html
    ├── Data_Investigations_Test.html
    ├── Ocean_Test_3rdGrade.html
    └── Ocean_Olympiad_Test.html
```

---

## Safety Requirements

| Event | Required Eyewear |
|---|---|
| Bridge Building | ANSI Z87+ impact glasses |
| Tower Building | ANSI Z87+ impact glasses |
| Astronaut Lander | ANSI Z87+ impact glasses |
| Bungee Egg Drop | ANSI Z87 **D3** splash/droplet goggles (full seal, "D3" on label) |
| Ocean, Data, Nervous System, Shock Value | None required |

Safety gear is **not provided** at events. Teams must bring their own. Competing without proper eyewear results in a no-show score.

---

## Tournament Schedule

| Date | Tournaments | Location |
|---|---|---|
| April 18, 2026 | Blueprint & Infrared | Oakton High School |
| April 25, 2026 | Chlorophyll & Dark Matter | Lake Braddock Secondary |

Teams compete in a morning or afternoon half-day session. Written events follow a fixed schedule; build events are coach-scheduled within designated time slots.

---

## Deploying on GitHub Pages

1. Create a public GitHub repository
2. Upload all files with `index.html` at the root (not inside a subfolder)
3. Go to **Settings → Pages**, set branch to `main`, folder to `/ (root)`
4. Your site will be live at `https://yourusername.github.io/repo-name/` within a minute

To update a page, edit the file directly in GitHub and commit — changes go live automatically.

---

## Source & Disclaimer

All rules, materials lists, scoring formulas, and event descriptions are drawn from the **2025–2026 VA Division A Tournament Rules Manual (v9.01)**. Study guides, slides, shopping lists, and practice tests are supplementary preparation resources and are not official VASO materials.

Per the rules manual, Division A does not release previous test questions. Practice tests in this portal are original study aids written for preparation purposes only.

- [VASO official site](https://www.virginiaso.org/div-a)
- [Science Olympiad national](https://www.soinc.org)
