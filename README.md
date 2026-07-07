<div align="center">

<img width="100%" src="./diagrams/status-bar.svg" />

</div>

<br/>

## Stack

<table>
<tr><td width="140"><sub>LANGUAGES</sub></td><td><img src="https://skillicons.dev/icons?i=cpp,java,py,js,ts,html,css&theme=dark" /></td></tr>
<tr><td><sub>FRONTEND</sub></td><td><img src="https://skillicons.dev/icons?i=react,vite,tailwind&theme=dark" /></td></tr>
<tr><td><sub>BACKEND / DATA</sub></td><td><img src="https://skillicons.dev/icons?i=nodejs,express,postgres,mongodb,prisma,fastapi&theme=dark" /></td></tr>
<tr><td><sub>TOOLING</sub></td><td><img src="https://skillicons.dev/icons?i=git,github,githubactions,vercel,postman,vscode&theme=dark" /></td></tr>
</table>

<br/>

<img width="100%" src="./diagrams/hairline.svg" />

<br/>

## Systems

Three shipped projects, each solving a distinct architectural problem rather than repeating a CRUD template.

### ForkTale — version control for prose

<img width="100%" src="./diagrams/forktale-architecture.svg" />

Story branching modeled as a self-referential commit DAG instead of a flat revision list, so forks, merges, and non-linear history behave the way Git's do — applied to creative writing instead of code. Forking clones `Story`, `Branch`, and `Commit` atomically inside one Prisma transaction, with a compound unique constraint blocking duplicate forks at the database layer rather than the application layer. Discovery-feed queries were N+1 until profiling caught it; nested Prisma includes brought that down to a single round trip. Frontend on Vercel, API on Railway, Postgres on Neon, CI as two parallel GitHub Actions jobs.

`React · TypeScript · Node.js · PostgreSQL · Prisma · JWT · Gemini 2.5 Flash` → [github.com/sakshamvarshney43/ForkTale](https://github.com/sakshamvarshney43/ForkTale)

### CodeEclipse — Java structure without a compiler

<img width="100%" src="./diagrams/codeeclipse-architecture.svg" />

Parses raw `.java` source with a hand-written brace-depth tokenizer — no `javac`, no AST library — and extracts inheritance, composition, aggregation, and dependency relationships directly from tokens. Renders as a force-directed graph with zoom, pan, and minimap, built for exploring hierarchies too large to read as a class list, with PNG/PDF export for sharing outside the tool.

`React · React Flow · Node.js · MongoDB` → [github.com/sakshamvarshney43/Code-Eclipse](https://github.com/sakshamvarshney43/Code-Eclipse)

### IngrediChef — recommendation from what's in the fridge

<img width="100%" src="./diagrams/ingredichef-architecture.svg" />

A user query filters 6,000+ recipes by cuisine, diet, and cook time; TF-IDF vectorization scores ingredient similarity; KNN ranks candidates. Served through a FastAPI microservice decoupled from the Node.js backend, so the recommendation layer scales independently of the rest of the app. Pantry tracking flags missing ingredients and generates grocery lists from what's already on hand.

`React · Node.js · Python · FastAPI · scikit-learn` → [github.com/sakshamvarshney43/IngrediChef](https://github.com/sakshamvarshney43/IngrediChef)

<br/>

<img width="100%" src="./diagrams/hairline.svg" />

<br/>

## Signal

<table>
<tr><td width="220"><sub>PROBLEM SOLVING</sub></td><td>1,500+ solved · LeetCode Knight (2015) · Codeforces Specialist (1414) · CodeChef 1641</td></tr>
<tr><td><sub>NEXTWAVE CPL</sub></td><td>Global rank 539 · college rank 28 of 1,900+ across IITs, NITs, IIITs</td></tr>
<tr><td><sub>ACADEMIC</sub></td><td>CPI 8.31 · Reliance Foundation Scholar, 5,000 of 1,00,000+ applicants</td></tr>
<tr><td><sub>OPEN SOURCE</sub></td><td>GSSoC 2025 — top 30 nationally, Silver Badge · Techfest IIT Bombay campus ambassador</td></tr>
</table>

<br/>

<img width="100%" src="./diagrams/hairline.svg" />

<br/>

## Activity

<div align="center">
<img width="49%" src="./profile/stats.svg" />
<img width="49%" src="https://streak-stats.demolab.com/?user=sakshamvarshney43&hide_border=true&background=10141B&stroke=1E2530&ring=3B82F6&fire=E5A93B&currStreakLabel=E5A93B&sideNums=E6E9EF&sideLabels=9AA4B2&dates=6B7480" />
</div>

<div align="center">
<img width="60%" src="./profile/top-langs.svg" />
</div>

<div align="center">
<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=sakshamvarshney43&hide_border=true&bg_color=10141B&color=E6E9EF&line=3B82F6&point=3B82F6&area=true&area_color=1E2530" />
</div>

<br/>

```yaml
now:
  building: [ForkTale collaborative editing, CodeEclipse dependency view]
  learning: [system design, distributed systems fundamentals]
  open_to: [SDE internships, full-stack roles, open source]
```

<br/>

<img width="100%" src="./diagrams/hairline.svg" />

<br/>

<div align="center">
<sub><a href="mailto:sakshamvarshney43@gmail.com">sakshamvarshney43@gmail.com</a> · <a href="https://linkedin.com/in/saksham0043">linkedin.com/in/saksham0043</a> · <a href="https://github.com/sakshamvarshney43">github.com/sakshamvarshney43</a></sub>
</div>

<div align="center">
<sub><a href="https://raw.githubusercontent.com/sakshamvarshney43/sakshamvarshney43/output/github-contribution-grid-snake-dark.svg">contribution snake ↗</a></sub>
</div>
