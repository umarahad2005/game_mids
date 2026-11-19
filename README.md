# OOP Game Programming — Midterm Prep

A single-page study guide for an OOP Game Programming (Unity / C#) midterm exam. It is a self-contained HTML page with no build step, set up to be deployed on Vercel.

## What's inside

The page is split into five tabs:

- **Overview** — paper format (40 marks: 10 objective, 12 short, 18 long/scripts) and a marks strategy table.
- **Concepts** — Unity update loops (`Awake`, `Start`, `Update`, `FixedUpdate`, `LateUpdate`), `Time.deltaTime`, access modifiers and `[SerializeField]`, triggers vs. collisions, the Singleton pattern, and `PlayerPrefs`.
- **FPS Game** — Rigidbody movement, shooting with `Instantiate`/`Destroy`, and mouse-look camera rotation.
- **Scripts** — complete reference scripts for movement, a gun/shooting script, a Singleton `GameManager`, and a bullet with collision handling.
- **Practice Q's** — scenario-style practice questions with expandable answers.

## Tech stack

- Plain HTML, CSS and vanilla JavaScript (tab switching and Q&A toggles)
- Google Fonts (Space Mono, Syne)
- Vercel for hosting (`vercel.json` rewrites `/` to `midsprac.html`)

## Project structure

```
.
├── midsprac.html   # the entire study guide (markup, styles, script)
└── vercel.json     # routes / to midsprac.html
```

## Running locally

No dependencies are needed. Open `midsprac.html` in a browser, or serve the folder with any static server, for example:

```bash
npx serve .
```

## Deployment

Import the repository into Vercel as a static project. The included `vercel.json` makes the site root serve `midsprac.html`.
